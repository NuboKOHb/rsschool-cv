# Aleksei, Spasiuk
1. Contact Info
  * mail spasiuk@overdrive.by
  * tel +375 29 888 28 17
2. Summary (your goal, wishes, reveal what is important for you, what do you want and why.
Some kind of self-presentation. In case of lack of experience  Junior Developer sells his/her potential, his/her passion and ability to learn fast. You shouldn't think that everybody is going to teach you when you come to the workplace . Rather being a Junior means always
learning new things from everywhere etc.).
3. Skills (e.g. programming languages, frameworks, methodologies, version control, tools etc.)
  * html
  * css
  * javascript
  * mysql
  * bash
  * powershell
  * nmap
4. Code examples (LATEST)
  ```javascript
      var maxSequence = function(arr){
      function getSumArray(arr) {
        return arr.length > 0 ? arr.reduce( (sum, current) => sum+current):0;
      }
      if(arr.length == 0) {
        return 0;
      }
      let maxSum = 0;
      let maxArr = [];
      for(let i = 0; i < arr.length; i++) {
        for (let j = 1; j <= arr.length - i; j++) {
          if (maxSum < getSumArray(arr.slice(i,i+j))) {
            maxArr = arr.slice(i,i+j);
            maxSum = getSumArray(maxArr);
          }
        }
      }
      return maxSum;
    }
  ```
5. Experience
  * https://lsys.by - project managment and develop transfer unit
  * https://lsys.su - full develop
6. Education (including courses, seminars, lectures, online learning)
  ![geekbrains](https://geekbrains.ru/users/1841524)
7. English (elaborate on what kind of practice you had, if any, how long it lasted and so on)
