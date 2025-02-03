var yourName = prompt("What is your name ?");

var correctSound = document.getElementById('coreectaudio'),
    wrongSound = document.getElementById('wrongaudio');



var definitionsNames = [
  "A place where people go to study.",
 "A place where people go to play.",
  "A place where people go to work.",
   "The activity or job of writing computer programs.",
   "A small animal like a mouse with wings that flies at night.",
   "Someone who takes part in a game or sport.",
   "A group of students who are taught together at school.",
   "Someone whose job is to teach in a school or college.",
   "The flat surface of a room on which you walk.",
   "Someone who keeps or examines the records of money received, paid, and owed by a company or person.",
   "Something that is part of a list or group of things.",
   "A line of people, usually standing or in cars, waiting for something.",
   "Conversation or reports about other people's private lives that might be unkind, disapproving, or not true.",
   "An ability to do an activity or job well, especially because you have practised it.",
   "An opinion that someone offers you about what you should do or how you should act in a particular situation.",
   "A set of mathematical instructions or rules that, especially if given to a computer, will help to calculate an answer to a problem.",
   "A written text that can be published in printed or electronic form.",
   "A legal document that states and explains a formal agreement between two different people or groups, or the agreement itself.",
   "A piece of writing on a particular subject in a newspaper or magazine, or on the internet.",
   "A set of classes or a plan of study on a particular subject, usually leading to an exam or qualification.",
   "An empty space in an object, usually with an opening to the object's surface, or an opening that goes completely through an object.",
   "The general name for a particular group of sports in which people compete, including running, jumping, and throwing.",
   "A test of a student's knowledge or skill in a particular subject.",
   "A period of time during which someone works for a company or organization in order to get experience of a particular type of work.",
   "The point, area, or line that is formed by the meeting of two lines, surfaces, roads, etc."
  
  ]

resultsOfPlace = definitionsNames [Math.floor(Math.random()*definitionsNames.length)];

document.getElementById('place').innerHTML = resultsOfPlace;

var mark = document.getElementById('mark');




function check() {

  "use strict";
  

  var result = document.getElementById('result'); 

  if (resultsOfPlace === "A place where people go to study.") {

      if (result.value === "School" || result.value === "school" || result.value === "School " || result.value === "school ") {

        mark.setAttribute('src', 'images/correct.png');
        correctSound.play()
        

      } else if (result.value === "") {

        
        alert("You have to write something ..")



      } else { 
        
        mark.setAttribute('src', 'images/wrong.png');
        wrongSound.play()

      }
      

  } else if (resultsOfPlace === "A place where people go to play.") {

    if (result.value === "Stadium" || result.value === "stadium" || result.value === "Stadium " || result.value === "stadium ") {

      mark.setAttribute('src', 'images/correct.png');
      correctSound.play()
      

    } else if (result.value === "") {


      alert("You have to write something ..")


    } else { 
      
      mark.setAttribute('src', 'images/wrong.png');
      wrongSound.play()

    }
    

} else  if (resultsOfPlace === "A place where people go to work.") {

  if (result.value === "Work" || result.value === "work" || result.value === "Work " || result.value === "work ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {


    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "The activity or job of writing computer programs.") {

  if (result.value === "Programming" || result.value === "programming" || result.value === "Programming " || result.value === "programming ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {


    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A small animal like a mouse with wings that flies at night.") {

  if (result.value === "Bat" || result.value === "bat" || result.value === "Bat " || result.value === "bat ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {


    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "Someone who takes part in a game or sport.") {

  if (result.value === "Player" || result.value === "player" || result.value === "Player " || result.value === "player ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {


    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

}  else if (resultsOfPlace === "A group of students who are taught together at school.") {

  if (result.value === "Class" || result.value === "class" || result.value === "Class " || result.value === "class ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {


    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "Someone whose job is to teach in a school or college." ) {

  if (result.value === "Teacher" || result.value === "teacher" || result.value === "Teacher " || result.value === "teacher ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {


    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "The flat surface of a room on which you walk.") {

  if (result.value === "Floor" || result.value === "floor" || result.value === "Floor " || result.value === "floor ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "Someone who keeps or examines the records of money received, paid, and owed by a company or person.") {

  if (result.value === "Accountant" || result.value === "accountant" || result.value === "accountant " || result.value === "Accountant ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

}  else if (resultsOfPlace === "Something that is part of a list or group of things.") {

  if (result.value === "Item" || result.value === "item" || result.value === "Item " || result.value === "item ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A line of people, usually standing or in cars, waiting for something.") {

  if (result.value === "Queue" || result.value === "queue" || result.value === "Queue " || result.value === "queue ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "Conversation or reports about other people's private lives that might be unkind, disapproving, or not true.") {

  if (result.value === "Gossip" || result.value === "gossip" || result.value === "Gossip " || result.value === "gossip ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "An ability to do an activity or job well, especially because you have practised it.") {

  if (result.value === "Skill" || result.value === "skill" || result.value === "Skill " || result.value === "skill ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "An opinion that someone offers you about what you should do or how you should act in a particular situation.") {

  if (result.value === "Advice" || result.value === "advice" || result.value === "Advice " || result.value === "adivce ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A set of mathematical instructions or rules that, especially if given to a computer, will help to calculate an answer to a problem.") {

  if (result.value === "Algorithm" || result.value === "algorithm" || result.value === "Algorithms" || result.value === "algorithms" || result.value === "Algorithm " || result.value === "algorithm " || result.value === "Algorithms " || result.value === "algorithms ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A written text that can be published in printed or electronic form.") {

  if (result.value === "Book" || result.value === "book" || result.value === "Book " || result.value === "book ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A legal document that states and explains a formal agreement between two different people or groups, or the agreement itself.") {

  if (result.value === "Contract" || result.value === "contract" || result.value === "Contract " || result.value === "contract ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A piece of writing on a particular subject in a newspaper or magazine, or on the internet.") {

  if (result.value === "Article" || result.value === "article" || result.value === "Article " || result.value === "article ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A set of classes or a plan of study on a particular subject, usually leading to an exam or qualification.") {

  if (result.value === "Course" || result.value === "course" || result.value === "Course " || result.value === "course ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "An empty space in an object, usually with an opening to the object's surface, or an opening that goes completely through an object.") {

  if (result.value === "Hole" || result.value === "hole" || result.value === "Hole " || result.value === "hole ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "The general name for a particular group of sports in which people compete, including running, jumping, and throwing.") {

  if (result.value === "Athletics" || result.value === "athletics" || result.value === "Athletics " || result.value === "Athletics ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A test of a student's knowledge or skill in a particular subject.") {

  if (result.value === "Exam" || result.value === "exam" || result.value === "Exam " || result.value === "exam ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "A period of time during which someone works for a company or organization in order to get experience of a particular type of work.") {

  if (result.value === "Internship" || result.value === "internship" || result.value === "Internship " || result.value === "internship ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

} else if (resultsOfPlace === "The point, area, or line that is formed by the meeting of two lines, surfaces, roads, etc.") {

  if (result.value === "Corner" || result.value === "corner" || result.value === "Corner " || result.value === "corner ") {

    mark.setAttribute('src', 'images/correct.png');
    correctSound.play()
    

  } else if (result.value === "") {

    
    alert("You have to write something ..")


  } else { 
    
    mark.setAttribute('src', 'images/wrong.png');
    wrongSound.play()

  }
  

}


};





function reset() {
 "use strict";


      document.getElementById('result').value = "";
      mark.setAttribute('src', 'images/think.png');

      var definitionsNames = [
        "A place where people go to study.",
       "A place where people go to play.",
        "A place where people go to work.",
         "The activity or job of writing computer programs.",
         "A small animal like a mouse with wings that flies at night.",
         "Someone who takes part in a game or sport.",
         "A group of students who are taught together at school.",
         "Someone whose job is to teach in a school or college.",
         "The flat surface of a room on which you walk.",
         "Someone who keeps or examines the records of money received, paid, and owed by a company or person.",
         "Something that is part of a list or group of things.",
         "A line of people, usually standing or in cars, waiting for something.",
         "Conversation or reports about other people's private lives that might be unkind, disapproving, or not true.",
         "An ability to do an activity or job well, especially because you have practised it.",
         "An opinion that someone offers you about what you should do or how you should act in a particular situation.",
         "A set of mathematical instructions or rules that, especially if given to a computer, will help to calculate an answer to a problem.",
         "A written text that can be published in printed or electronic form.",
         "A legal document that states and explains a formal agreement between two different people or groups, or the agreement itself.",
         "A piece of writing on a particular subject in a newspaper or magazine, or on the internet.",
         "A set of classes or a plan of study on a particular subject, usually leading to an exam or qualification.",
         "An empty space in an object, usually with an opening to the object's surface, or an opening that goes completely through an object.",
         "The general name for a particular group of sports in which people compete, including running, jumping, and throwing.",
         "A test of a student's knowledge or skill in a particular subject.",
         "A period of time during which someone works for a company or organization in order to get experience of a particular type of work.",
         "The point, area, or line that is formed by the meeting of two lines, surfaces, roads, etc."
        ]
      

      
      resultsOfPlace = definitionsNames [Math.floor(Math.random()*definitionsNames.length)];
      
      document.getElementById('place').innerHTML = resultsOfPlace;


};

function finish() {
  "use strict";

  alert("Thanks " + yourName + " for your experiment and I hope you enjoyed it.")


}










