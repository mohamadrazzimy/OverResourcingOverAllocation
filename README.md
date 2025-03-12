### MS Project — Handling Over-Resourcing and Over-Allocation

![](https://cdn-images-1.medium.com/max/1000/0*XsPBDY2wWm6wiRNH)

Photo by [Nubelson Fernandes](https://unsplash.com/@nublson?utm_source=medium&utm_medium=referral) on [Unsplash](https://unsplash.com?utm_source=medium&utm_medium=referral)

Over-resourcing and over-allocation are two related but distinct concepts in project management, particularly when using tools like Microsoft Project.

Over-resourcing:  
Over-resourcing refers to the situation where a task or activity has more resources (e.g., people, equipment, or materials) assigned to it than are actually required to complete the work. This can happen when:

1.  **Unnecessary Resources**: More resources are assigned to a task than are needed to get the work done effectively.
2.  **Resource Sharing**: Resources are assigned to multiple tasks or projects simultaneously, resulting in inefficient utilization.
3.  **Incorrect Resource Estimates**: The required resource effort for a task is overestimated during the planning phase.

Over-resourcing can lead to increased project costs, inefficient use of resources, and potential conflicts or confusion among team members.

Over-allocation:  
Over-allocation refers to the situation where a resource (e.g., a person) is assigned to work on too many tasks or activities simultaneously, resulting in their being overcommitted or overloaded. This can happen when:

1.  **Unrealistic Task Assignments**: A resource is assigned to more tasks than they can reasonably complete within the given time frame.
2.  **Insufficient Resource Capacity**: The total effort required for all the tasks assigned to a resource exceeds their available work time or capacity.
3.  **Lack of Resource Leveling**: The project schedule does not properly balance the workload across resources.

Over-allocation can lead to delays, decreased productivity, burnout, and quality issues, as the overloaded resource struggles to juggle multiple competing priorities.

  

### MS Project Example

The following steps demonstrate the Over-Resourcing and Over-Allocation occurrences in MS Project application.

### [1] Create a new project

  

![](https://cdn-images-1.medium.com/max/1000/1*jw8EC57tiyZx9tWGUIaD9g.png)

In this tutorial, we name the project as `ProjectX`.

By default, this project uses the Standard work calendar.

![](https://cdn-images-1.medium.com/max/1000/1*WYz-B1FbrZy7DyEiwOSJKw.png)

  

### [2] Check project configuration

#### [2.1] Project Options

Access via File menu i.e. File/Options, and then in the Project Options window select Schedule.

Set:

-   New tasks created = Auto Scheduled
-   Duration is entered in = Days
-   Work is entered in = Hours
-   Default task type = Fixed Duration
-   New tasks are effort driven = No
-   Show task schedule warnings = Yes
-   Show task schedule suggestions = Yes

![](https://cdn-images-1.medium.com/max/1000/1*ef6DYhcEZe6zgCxUt0XEMw.png)

  

#### [2.2] Resource Leveling Options

Set:

-   Leveling calculations = Manual
-   Resolving over-allocations → Uncheck all options

![](https://cdn-images-1.medium.com/max/1000/1*65B9hVRcqpCXzZiWY2OTWg.png)

  

### [3] Task entries

Enter tasks t1, t2, t3.

![](https://cdn-images-1.medium.com/max/1000/1*Mh8FrLR_li2Qh50B_4Ng3A.png)

  

### [4] Resource entries

Right-click task t1, select context menu `Information…`.

![](https://cdn-images-1.medium.com/max/1000/1*gRKd7gwofTS9xUIIlsoJ8A.png)

  

In the `Resources` tab of the `Task Information` dialog window, enter Resources r1, r2, r3, r4.

![](https://cdn-images-1.medium.com/max/1000/1*JwVTKDjSCAqYzYAGVEPzPw.png)

Click OK.

### [5] View Task Usage.

Click the `View Type` button in the `Task` ribbon and select `Task Usage` view.

![](https://cdn-images-1.medium.com/max/1000/1*UrwdItQ4FpoLLwJeIgvEag.png)

Notice that MS Project has set 32 work hours for the combination of four work resources that have been entered in the previous step.

![](https://cdn-images-1.medium.com/max/1000/1*4fGDZKLJOhtlhqs2nnaV5A.png)

Change the work hours from 32 to 24.

Notice that there is a green icon indicator on top left of the work hour cell. If you hover over the icon, a warning pop up action message appears which tells you that “You have decreased the amount for this task” and ask your next action i.e. either to “Decrease duration but keep the hours resources work per day (units) the same” or “Decrease the hours resources work per day (units) the same”.

![](https://cdn-images-1.medium.com/max/1000/1*5WbmiBgxcSNulXhMWmYVcQ.png)

As this project is using Standard Calendar (8 work hours per day), having four work resources will give a total of 8*4=32 which is exceeding the 24 hours planned work hours. This is an indication of **Over-Resourcing occurrence** i.e. amount of resources work hours is more than planned task work hours.

Ignore the messages and actions first.

Let’s move on to Over-Allocation example.

### [5] Add More Resource entries

Right-click task t2, select context menu `Information…` .

![](https://cdn-images-1.medium.com/max/1000/1*wV5055LlF_iE7ke9p5irqw.png)

Add the same resources to the task.

![](https://cdn-images-1.medium.com/max/1000/1*gij1zUeFXO1JetqALdrczQ.png)

Notice that there are red person warning icons in the info column for tasks t1 and t2. These are an indication of resource **Over-Allocation occurrence** i.e. there are some work resources that have been allocated to tasks beyond their available hours.

![](https://cdn-images-1.medium.com/max/1000/1*JSOVrVJPG7pFaUPMFVEZog.png)

Right-click the icon for task t2, select Fix in Task Inspector.

![](https://cdn-images-1.medium.com/max/1000/1*ZPCP94uJZjArMDa9vXCGaQ.png)

The Task Inspector panel will appear on the left side of the application window. It will suggest some action to overcome the resource Over-Allocation problem in the above step.

![](https://cdn-images-1.medium.com/max/1000/1*HDgVOkARLg10iUL13Ef3xA.png)

  

### Download example:

[**ProjectX.mpp**  
_Edit description_drive.google.com](https://drive.google.com/file/d/1hlA4eVHNAu-56JoyVITxjRogPrqEsI-L/view?usp=sharing "https://drive.google.com/file/d/1hlA4eVHNAu-56JoyVITxjRogPrqEsI-L/view?usp=sharing")[](https://drive.google.com/file/d/1hlA4eVHNAu-56JoyVITxjRogPrqEsI-L/view?usp=sharing)

  

### 🤓

https://medium.com/p/4fc9368424c1
