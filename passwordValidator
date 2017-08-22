/* TASK:

PASSWORD VALIDATOR We are going to write a program to make sure that a password is complex so that it cannot be easily guessed. Our password validator will check multiple aspects of a potential password and will report back to the user if their password meets a set of rules.

The rules for our password validator are:

Has at least one uppercase letter
Has at least one lowercase letter
Is at least 8 characters long
Has at least one special character*/



//function for uppercase
function hasUppercase(input){
  
  for(var i = 0; i < input.length; i++){
    
    if(input.charAt(i) === input.charAt(i).toUpperCase()){
       return true;
       }
    
  }
  
}

//function for lowercase
function hasLowercase(input){
  
  for(var i = 0; i < input.length; i++){
    if(input.charAt(i) === input.charAt(i).toLowerCase()){
      	return true;
       
       }
    
  }
  
}

//function for isLongEnough
function isLongEnough(input){
  if(input.length > 8){
    return true
  }
  
  
}

//function for special

function hasSpecialCharacter(input){
  
  var specialCharacters = ['$','#','@','!']
  for(var i = 0; i < input.length; i++){
    for(var j = 0; j < specialCharacters.length; j++){
      if(input.charAt(i) === specialCharacters[j]){
         return true;
         }
      
      
    }
  }
  
}

//function for reporting of complexity 
function isPasswordValid(input){
  
  //hasUpperCase() If
  if(hasUppercase(input)){
    console.log('Valid Password - Has Capital');
   
     
     }
  //!hasUpperCase() If
  if(!hasUppercase(input)){
    console.log("Needs Capital");
    
  }
  
  //hasLowercase()
  if(hasLowercase(input)){
    console.log('Valid Password - Has Lowercase');
    
     
     }
  
  //!hasLowercase()
  if(!hasLowercase(input)){
    console.log('Needs Lower Case');
  }
  
  //isLongEnough()
  if(isLongEnough(input)){
    console.log('Valid Password - Is Long Enough');
     }
  
  
  //!isLongEnough()
  if(!isLongEnough(input)){
    console.log('Not Long Enough');
    
     
     }
  
  
  //hasSpecialChar
	if(hasSpecialCharacter(input)){
  	 console.log('Valid Password - Has Character');
	}
  //!hasSpecialChar
  if(!hasSpecialCharacter(input)){
  	 console.log('Needs Character');
	}
}

isPasswordValid('kDsdWQskjdskR!');


