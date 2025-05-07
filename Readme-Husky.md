<h1>Husky</h1>

<p>Husky is a tool tht implements git hooks , Hooks are steps executed before certain actions being done on github like pull,push. What husky does is it executes these hooks when certain actions are triggered in github. We should configure a script in husky and this will execute just before that action. If there are no errors the action takes place. If it has an error the action does not perform and instead a error in terminal is displayed.</p>

<h2> How can we use this? </h2>

<p>For example there might be a case where we need to lint (checking syntax errors in a code) . Without checking syntax someone commits and it might cause an error. So Husky in that hooks checks if linting is already done or we can write a script to do the linting. Like this  </p>
