# PT-CI_CD

Build a deployment pipeline to deploy a Hello world app in Python or Node using GitHub Actions.

# My Steps

1. created a new github repo with "simple workflow" config. by clicking on the repo's "Actions" button, hence created a basic main.yml file for our simple app.

2. Added this code in main.yml file :-
   steps:

   - uses: actions/checkout@v3
   - uses: actions/setup-node@v3
     with:
     node-version: 18
   - run: npm install

   In Order to run our Nodejs app.

3. Created src folder with 2 files named app.js and index.js with appropriate code and also created a package.json just to check the code locally.

4. Reference Blog :- https://blog.logrocket.com/ci-cd-node-js-github-actions/
