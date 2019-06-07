## Environment variables in Vue cli 3 app

**SET**  

Staging for example : 

Set up the file named ".env.staging" and place in project root folder.   
The variable name be prefixed with 
"<span span style="color:red">VUE_APP_</span>"  
```
VUE_APP_TITLE=sample_data
```

**USE**  in javascript
```
process.env.VUE_APP_TITLE
```

**BUILD**  
```
vue-cli-service build --mode staging
```


ref:  
https://cli.vuejs.org/guide/mode-and-env.html#environment-variables

