# Zakorukin Vladislav

## Contact Information

* GitHub: [zakowsk1](https://github.com/zakowsk1)
* Discord: [peroxidee](https://discord.com/users/peroxidee)

## About me

Beginner frontend developer.
I'm in my 3rd year of university, taking RS school course and learning programming on my own.

## Skills

* HTML 5
* CSS 3
* JavaScript
* Git/GitHub

## Code Example

```.
function Bogosort(a) {
    function isSorted(a) {
        for(let i = 1; i < a.length; i++)
            if (a[i-1] > a[i])
                return false;
        return true;
    };

    function shuffle(a) {
        for (let i = a.length - 1; i > 0; i--) {
            let j = Math.floor(Math.random() * (i + 1)); 
            [a[i], a[j]] = [a[j], a[i]];
        }
        return a;
    }

   function sort(a) {
        while(!isSorted(a))
            a = shuffle(a);
        return a;
    }
    
    return sort(a);
}
```

### Education

* Processing
  * Federal State Budget-Financed Educational Institution of Higher Education The Bonch-Bruevich Saint Petersburg State University of Telecommunications (Student)
    * RS School Javascript stage #1
* Finished
  * Sololearn: Web-developmet course
  * Sololearn: Javascript course

### Languages

Russian (native)
English (B2)
