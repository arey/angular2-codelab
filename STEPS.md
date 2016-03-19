## Step 1: setting up the environment

1. clone branch: https://github.com/manekinekko/angular2-codelab/tree/step-1
2. create and add a root component
  - name it `Ng2CodelabApp`
  - store it in `src/app/ng2-codelab.ts` 
  - use selector `<app></app>`
  - create and use the template `src/app/ng2codelab.html`
3. bootstrap your application in `src/app.ts`
4. **[optional]** check solution: https://github.com/manekinekko/angular2-codelab/tree/step-1-solution

## Step 2: home and theme-card components

1. clone branch: https://github.com/manekinekko/angular2-codelab/tree/step-2
2. create and add a **dump** component
  - name it `ThemeCard`
  - store it in `src/app/components/theme-card/theme-card.ts`
  - use selector `<theme-card></theme-card>`
  - use template `src/app/components/theme-card/theme-card.html`
3. create and add a **smart** component
  - name it `Home` 
  - store it in `src/app/components/home/home.ts`
  - use selector `<home></home>`
  - use template `src/app/components/home/home.html`
  - use the provided service `src/app/services/technologies-store/technologies-store.ts`
4. **[optional]** check solution: https://github.com/manekinekko/angular2-codelab/tree/step-2-solution

## Step 3: setting up the router and question component

1. clone branch: https://github.com/manekinekko/angular2-codelab/tree/step-3
2. create and add a **dump** component
  - name it `QuestionCard` 
  - store it in `src/app/components/question-card/question-card.ts`
  - use selector `<question-card></question-card>`
  - use template `src/app/components/question-card/question-card.html`
3. add a route configurtion to the root component `Ng2CodelabApp`
  - add two routes: `Home` and `QuestionCard`
4. update the `ThemeCard` and it template to use the router
5. update the `Ng2CodelabApp` template with the router directive
6. include the necessary router proviers in `src/app.ts`
  - use `PathLocationStrategy`
- **[optional]** check solution: https://github.com/manekinekko/angular2-codelab/tree/step-3-solution


## Step 4: technology component

> In this step, you are provided with all the necessary files containing the heavy work so you can focus on the basics. You can still take a momment and read this commit diff to understand what's really happening https://github.com/manekinekko/angular2-codelab/commit/39b9f0e6748825b51456d18dcd1cdd8d280fec7f

1. clone branch: https://github.com/manekinekko/angular2-codelab/tree/step-4
2. update the `QuestionCard` component and its template so it can display and navigate the questions correctly
  - use the elvis operator to allow parsing undefined values, ie: `{{question?.title}}`
3. if you like challenges, you can re-implement these files:
  - `src/app/components/technology/technology.ts`
  - `src/app/services/question-store/question-store.ts`
  - `src/app/services/session-store/session-store.ts`
- **[optional]** check solution: https://github.com/manekinekko/angular2-codelab/tree/step-4-solution

@todo

## Step 5: summary component

1. clone branch: https://github.com/manekinekko/angular2-codelab/tree/step-5
- **[optional]** check solution: https://github.com/manekinekko/angular2-codelab/tree/step-5-solution

@todo