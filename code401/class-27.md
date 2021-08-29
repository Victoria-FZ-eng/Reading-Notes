# Intents, Activities, and SharedPreferences

**A task** is a collection of activities that users interact with when performing a certain job. The activities are arranged in a stack—the back stack)—in the order in which each activity is opened.

## default behavior for activities and tasks:

1. When Activity A starts Activity B, Activity A is stopped, but the system retains its state (such as scroll position and text entered into forms). If the user presses the Back button while in Activity B, Activity A resumes with its state restored.
2. When the user leaves a task by pressing the Home button, the current activity is stopped and its task goes into the background. The system retains the state of every activity in the task. If the user later resumes the task by selecting the launcher icon that began the task, the task comes to the foreground and resumes the activity at the top of the stack.
3. If the user presses the Back button, the current activity is popped from the stack and destroyed. The previous activity in the stack is resumed. When an activity is destroyed, the system does not retain the activity's state.
4. Activities can be instantiated multiple times, even from other tasks.

*check references to see how you can use manifest attributes and intent flags to define how activities are associated with tasks and how they behave in the back stack.*




**A SharedPreferences** object points to a file containing key-value pairs and provides simple methods to read and write them. Each SharedPreferences file is managed by the framework and can be private or shared.

* You can create a new shared preference file or access an existing one by calling ( getSharedPreferences() OR getPreferences() ).

* To write to a shared preferences file, create a SharedPreferences.Editor by calling edit() on your SharedPreferences.

* To retrieve values from a shared preferences file, call methods such as getInt() and getString(), providing the key for the value you want, and optionally a default value to return if the key isn't present. 



References :
* [Android Tasks and the Back Stack](https://developer.android.com/guide/components/activities/tasks-and-back-stack)
* [Android SharedPreferences](https://developer.android.com/training/data-storage/shared-preferences)

