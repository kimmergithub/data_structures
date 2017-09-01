MOBIL FIRST DESIGN:
=== Media Queries
=== Start small device work up
=== viewport meta tag in the html
=== when the view port is === run this css... 320x



// Installed npm packages: jquery underscore request express
// jade shelljs passport http sys lodash async mocha chai sinon
// sinon-chai moment connect validator restify ejs ws
//co when helmet wrench brain mustache should backbone forever debug jsdom


// ==========================================================================
//    ==========      MY NPM INSTALL IS COMMENTED OUT HERE   ========

// npm install jquery underscore request express jade shelljs passport http sys lodash async
// mocha chai sinon  sinon-chai moment connect validator restify ejs ws co when helmet wrech brain
// mustache should backbone forever debug jsdom --save-dev


function subStringFinder(string) {
    let splitString = string.split('');
    let answer = [];
    for (var i = 0; i < string.length; i++){
        if ( ( answer.indexOf(string[i]) === -1 ) && ( string[i + 1] !== string[i + 2] )  ){
            answer.push(string[i])
        }
    }   
    let answerJoin = answer.join('');
        console.log(answerJoin);
        return answerJoin

    }

subStringFinder('abcabcbb');
subStringFinder('bbbbb');
subStringFinder('pwwkew');

//Excersise:
//Find the first longest substring which has no repeated characters
//Given "abcabcbb", the answer is "abc", which the length is 3.
//Given "bbbbb", the answer is "b", with the length of 1.
//Given "pwwkew", the answer is "wke", with the length of 3.
//Note that the answer must be a substring, "pwke" is a subsequence and not a substring.



var _ = require('underscore');

var evens = _.reject([1, 2, 3, 4, 5, 6], function(num){ return num % 2 != 0; });

console.log("Evens");
console.log(evens);
