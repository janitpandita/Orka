This website was live for sometime on netlify till it was free.
1. This is the home page of the website 
   ![image](https://github.com/user-attachments/assets/16641dac-c154-4aeb-8161-ff94aae4b3b8)
   
2.We can solve the question in more than 16 Languages 
   ![image](https://github.com/user-attachments/assets/1e420d55-c38d-4fa1-8af8-0ef800386768)
   
3.Here we have also implemented the feature of Dark Mode in it, so when ever we click on it the background changges to black colour
    a.this is the picture in light mode
        ![image](https://github.com/user-attachments/assets/15be845e-9968-4f08-9e9a-ddb58501def9)

   b. this is the picture in dark mode
        ![image](https://github.com/user-attachments/assets/04b72d53-13ca-4c51-899b-789e1d749568)
   
4. In the compiler option we can work on code in language after selecting it
   ![image](https://github.com/user-attachments/assets/4edac9c8-a135-4473-97df-ac02846fb69d)
   
5.  Here in the problem section we can find all the problems that we have solved in it and all the questions that are present there and we can solve it
   ![image](https://github.com/user-attachments/assets/26a44847-88fc-4b57-ac1d-6afda7f2412b)

6. We can also sign into it to see our current progress in it and all problems solved and all problems to solve
    ![image](https://github.com/user-attachments/assets/152ae718-1af3-41ee-b338-65c3d51544d9)
    ![image](https://github.com/user-attachments/assets/df5b12aa-e0e4-4444-b6b2-167f2a4d65c2)
    ![image](https://github.com/user-attachments/assets/cfa51f0e-df66-4f52-b2dc-7b2885643a05)





 





## Getting Started

First, run the development server:


```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```




<!--  todo 1. remove console.logs and error logs  -->
<!--!! todo 2. make function components server wherever possible -->
<!--!! 2. add a navbar for signin -->
<!-- done but need customizing  -->

<!--todo 4. connect to db and store user data PRIMARY-->

<!--todo 4. find a way to make question easy SECONDARY-->

<!-- step 1. provide user an interface to write problem statements uing word like editor which converts it into HTML -->
<!-- step2: the user specifies function name input type and output type-->
<!-- step 3: user clicks submit button and a server action is run which converts the data in json format  -->
<!-- step 4: it also connects to database and stores the question in teh data base -->
<!-- step 5: -->

<!--!! todo 5. add env variables to local file -->
<!-- added except python3_8 -->

<!--!! todo 6. create function to run and submit : -->


<!--todo 7. to fix the black space below body : SECONDARY-->

<!--todo 8: bring the boilerplate and function names : SECONDARY -->
<!-- step1: on submit button clicking a popup below should open with loading sign  -->
<!-- step2: when request answered then either show the error in the editor or show the accepted result logo -->
<!-- OPTIONAL FEATURE: switch to code mirror to highlight a line on error -->
<!--!! step3: we also need a way for user to close the popup that opened -->
<!--!! step4: we also need to convert it into binary and download it all manually --> 
        <!-- !!soln:just parse as text -->
<!--!! step5: we also need a way to stop executing get results when result is obtained -->
        <!-- done  -->
<!-- step6: we need a way to highlight in the line where the error is and not reset the page SECONDARY-->

<!-- todo 7. chnage theme of signin and editor page to black or grey:secondary -->
<!-- todo 9: theme option: secondary -->

<!-- username : advaitasoni-->
<!-- db:password jKqeQ6SI2N2mwCOv -->

ERROR CODE:
<!-- code is  CODE_COMPILED
----Final Show is ----
: {
  he_id: '44136cb1-c581-4f51-9442-134478e94a3c',
  request_status: { code: 'CODE_COMPILED', message: 'Compilation step is over' },
  status_update_url: 'https://api.hackerearth.com/v4/partner/code-evaluation/submissions/44136cb1-c581-4f51-9442-134478e94a3c/',
  result: {
    compile_status: '  File "solution.py3", line 1\n' +
      '    this is a code for python\n' +
      '              ^\n' +
      'SyntaxError: invalid syntax\n' +
      '\n',
    run_status: {
      output: null,
      status: 'NA',
      status_detail: null,
      time_used: 0,
      memory_used: 0
    }
  }
} -->
SUCCESS" CODE:
<!-- : {
  he_id: '19d32f89-146c-47f2-b34d-80085c0883de',
  request_status: {
    code: 'REQUEST_COMPLETED',
    message: 'Your request has been completed successfully'
  },
  status_update_url: 'https://api.hackerearth.com/v4/partner/code-evaluation/submissions/19d32f89-146c-47f2-b34d-80085c0883de/',
  result: {
    compile_status: 'OK',
    run_status: {
      output: 'https://he-s3.s3.amazonaws.com/media/userdata/AnonymousUser/code/faada16',
      status: 'AC',
      status_detail: 'NA',
      time_used: 0.0175,
      memory_used: 2
    }
  }
} -->

Waiting code:
<!-- : {
  he_id: 'fb1dc997-85e7-4d87-800f-fa036e8bb04b',
  request_status: { code: 'CODE_COMPILED', message: 'Compilation step is over' }, 
  status_update_url: 'https://api.hackerearth.com/v4/partner/code-evaluation/submissions/fb1dc997-85e7-4d87-800f-fa036e8bb04b/',
  result: {
    compile_status: 'OK',
    run_status: {
      output: null,
      status: 'NA',
      status_detail: null,
      time_used: 0,
      memory_used: 0
    }
  }
} -->
//status detail : "NA" means accepted
//result compile status for waiting or error
