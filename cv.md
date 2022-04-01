# Naumionak Aliaxandr 
## Engineer designer
----

### Contact:

**Phone**:+375295138467 \
**E-mail:** itchipset@gmail.com\
**Discord nikename:** Alex Naum (@sanches311)\
**Location:** Minsk, Belarus

___
### About myself
In 2010 year I graduated [High State College of Telecommunication](http://bsac.by/) and started to work engineer designer in State company. I designer telecommunication system, cable system, alarm system end etc. In 2014 year moved to position Team Leader. I want to develope application uses JavaScript, HTML and CSS.
___

### Education
Technician of telecommunication\
[Vitebsk company branch High State College of Telecommunication](https://vfbsac.by/)\  
2003-2007\
Vitebsk, Belarus\
Engineer of telecommunication\
[High State College of Telecommunication](https://vfbsac.by/)
2007-2010\
Minsk, Belarus\

**Courses:**
* Cisco CCNA;
* Rolling school;
___
### My skills:
* JS
* HTML
* CSS
* GitHub, Git
___
### Code example in JavaScript:
```
function solution(list){
        let count = 0;
        let formatedList = [];
         for (let i = 0; i <list.length; i++) {
            while (list[i+1] - list[i] == 1)
             { count++; 
             i++;
             }

        if (count == 0 ) { formatedList.push(list[i]);} else 
        if (count == 1) { formatedList.push(list[i-count]); formatedList.push(list[i]); count = 0;}
          else {formatedList.push(list[i-count] + "-" + list[i]);
        count = 0;}
        }
        return formatedList.toString();
}
```




