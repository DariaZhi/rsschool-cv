# Daria Zhilich

## _Contacts_

* __phone:__ +375(29)6383507
* __email:__ iamlucky.da@gmail.com
* __telegram:__ @daria_zhi

## _About Me_

I have rich experience as an assistant to the CEO in an IT and now I willing to go to another side of the fence as frontend developer.

## _Work Experience_

*2011 - 2021:*   assistant to the CEO at [RichBrains](https://richbrains.net)    
*2008 - 2011:*   croupier in the casino

## _Skills_

HTML, CSS, JavaScript, git, VSCode, Notion, Outlook, Jira

## _Code example_
```
const clockElement = document.createElement('h1')
document.body.append(clockElement)
clockElement.setAttribute('style', 'margin: 100px; font-family: -apple-system, "Helvetica Neue"; font-size: 42px; font-weight: 100')

function transformTime(time) {
    return time < 10 ? `0${time}` : time
    // if (time < 10)
    //     time = `0${time}`
    // else time = time
    // return time
}

function buildTemplateTime() {
    const currentDate = new Date()

    let hour = currentDate.getHours()
    hour = transformTime(hour)

    let minute = currentDate.getMinutes()
    minute = transformTime(minute)

    let sec = currentDate.getSeconds()
    sec = transformTime(sec)

    const ourTime = `${hour}:${minute}:${sec}`
    clockElement.textContent = ourTime
}

const timer = setInterval(buildTemplateTime, 1000)
```

## _English level_

B1   

## _Education_

*2021 - present:*   Frontend-developer course at [MyFreedom](https://myfreedom.by)  
*2015 - 2017:*   English at [Moonlight](https://mlight.by)


## _Websites & Social links_

My page on [LinkedIn](https://www.linkedin.com/in/daria-zchilich-8a67a631/)  
My [Facebook](https://www.facebook.com/dasha.zhilich) account