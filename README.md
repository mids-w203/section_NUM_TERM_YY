# Template for Section Specific Repositories
Use this repository as a template to create your section sprecific course repositories. 

## How to Use?
https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template

### Best Practices
To be consistence across sections, rename the newly generated repo as follows:

NUM = section no, i.e., 08

TERM = fa, sp, or su

YY = 20, 21, etc.

For an example, "section_08_fa_20" is a valid name.

## Github Actions
Any repository generated from this template will contains Github Actions to automate the following weekly routines: 
- Release weekly homework
- Release homework solution

### Initialization Steps
Here are the steps to activate and customize the actions for your section repo.
1. Create a personal access token (https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token).
   For step 6, a good descriptive name woudl be "W203 token". In step 7, select "repo". Generate the token, and make sure to copy it.
   We need it in the following step. 
2. Go to your section repository, then *Settings* -> *Secrets*.
3. Click on the "New Secret" button to create a new *secret variable* with the name *W203*. In the *value* field, paste the copied access token
   from step 1.

   **Note:** Your acceess token and this secret should be kept secret. Grant your students only read/write permission. They will not have
   access the secret unless you give them admin rights.
