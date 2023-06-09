# Module 2 Group Assignment

CSCI 5117, Spring 2022, [assignment description](https://canvas.umn.edu/courses/291031/pages/project-2)

## App Info:

* Team Name: Mutiny
* App Name: hocus-focus
* App Link: <https://hocus-focus-mutiny.web.app/>

### Students

* Kinza, Ahmed ahme0170@umn.edu
* Christina, Nguyen nguy4477@umn.edu
* Suihan, Dong dongx460@umn.edu
* Yizhe, Wang wang5959@umn.edu


## Key Features

**Describe the most challenging features you implemented
(one sentence per bullet, maximum 4 bullets):**

* Focus Timer: Tracking the state/sequence of events across multiple components


Which (if any) device integration(s) does your app support?

* Both web and mobile

Which (if any) progressive web app feature(s) does your app support?

* Notifications even when tab is not active (not compatible with Safari iOS)



## Mockup images

Main page (logged in)

![image](https://user-images.githubusercontent.com/43075531/161647863-aec0dc15-9f07-44da-9330-c8f06871ea4b.png)

Summary modal of main page (logged in; happens after a user completes their 'goal' number of sessions)

![image](https://user-images.githubusercontent.com/43075531/161648020-157b01db-96fb-4a4c-ad29-1f0c3cde947f.png)

Settings modal of main page (viewable and editable by anyone)

![image](https://user-images.githubusercontent.com/43075531/161648124-6a34e9e0-a6d8-48b2-b827-fef706a82a0a.png)

Leaderboard (viewable by anyone)

![image](https://user-images.githubusercontent.com/43075531/161647903-43b0b9bd-8a3e-4b45-9fda-a65de4cd848b.png)

Tasks page (logged in)

![image](https://user-images.githubusercontent.com/43075531/161647951-4cc2d4a9-d600-4c2c-9113-c8c43058ec6a.png)

Login page

![image](https://user-images.githubusercontent.com/43075531/161648156-d05050d0-ee1d-4ec1-89d5-b76c7ea3fb62.png)


## Testing Notes

**Is there anything special we need to know in order to effectively test your app? (optional):**

* Review info modal describing pomodoro technique to see how sequence of events plays out
* Additional definitions:
  * A `session` is the entire block the user plans to sit down and work for and is composed of `cycles`
  * A `cycle` is a sequence of `short break`, `long break`, and `focus`/`pomodoro` `intervals`
    * Traditionally, the sequence is `pomodoro`, `short`, `pomodoro`, `short`, `pomodoro`, `long`
    * A `long break delay` is the number of `pomodoro` intervals a user must complete before they get to take their `long` break
    * `autostart breaks`, if set to `true`, will automatically start the timer for the next interval when the first interval is over



## Screenshots of Site (complete)

HomePage:

On the homepage, if users are not loged in, they can only use the timer with the default value. After user loged in, they can set their own value for the timer, add tasks and track them. In addition, only the tasks that are not finished yet will show on the homepage. Tasks can be orgainzed by tags, and are able to be edited by clicking.
* Web Homepage:

![](/screenshot/homepage.png?raw=true "Homepage")

* Mobile Homepage:

![](/screenshot/mhome.png?raw=true "MobileHome")

TaskPage:
All tasks that user has created will show in this page, user can add, edit, delete tasks and filter tasks with the tags.

* Web Taskpage:

![](/screenshot/tasks.png?raw=true "Taskpage")

* Moblie Taskpage:

![](/screenshot/task.png?raw=true "MobileTask")

RankingPage:
* Web Rankingpage:

![](/screenshot/rankings.png?raw=true "Rankingpahe")

* Mobile Rankingpage:

![](/screenshot/mranking.png?raw=true "MobileRanking")

HelpPage:
Showing how to use this app.
* Web Helppage:

![](/screenshot/info.png?raw=true "Helppage")

* Moblie Helppage:

![](/screenshot/minfo.png?raw=true "MobileHelp")


TimerSettingPage:
* Web TimerSetting page:

![](/screenshot/setting.png?raw=true "TimerSetting")

![](/screenshot/msetting.png?raw=true "MobileSetting")


Requesting permission to send notifications:
<img width="921" alt="image" src="https://user-images.githubusercontent.com/43075531/166171165-a9cd4092-6d3e-4ef0-8475-d1864ddb50ea.png">

Summary Modal:
<img width="903" alt="image" src="https://user-images.githubusercontent.com/43075531/166171512-ae8fdc13-b4d6-4907-912a-2383cb0625ce.png">


## External Dependencies

**Document integrations with 3rd Party code or services here.
Please do not document required libraries (e.g., Vue, Vuefire, Firebase).**

* Tailwind Elements: Tailwind Modal/Dialog component for the pop up window for timer-setting, summary, information(help) page, login 
* toggle for the auto-break button
* Circular timer

**If there's anything else you would like to disclose about how your project
relied on external code, expertise, or anything else, please disclose that
here:**

...
