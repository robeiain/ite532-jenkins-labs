# Jenkins configurations

## Getting Familiar with Jenkins Console
When you login to jenkins for the first time, following is the screen you would see.
![Jenkins Welcome Screen](images/configurations/jenkins_console.jpg)

* On the left side of the screen, on top is the menu to  create new projects, to manage jenkins, to create users etc.
* Just below the menu is the build queue. All  jobs scheduled to run get added to the queue and would appear here.  
* Below build queue is the build executor status. This shows the status of the jobs being executed in real time.
* Bottom right of the page is the information about jenkins version displayed.

## Configuring Global Security
* Select  Manage Jenkins -> Configure Global Security
* Inspect the options, no need to change anything here



## Plugins

 The real magic of Jenkins lies in its rich plugins eco system. This is how tools integrate with jenkins to build a CI workflow. You want to trigger jenkins jobs after every change going into git, you have a plugin for it. You want to send a notification to your developers on a successful or failed builds, you have a notification plugin. You want to use a tool to fetch or push the build artifacts, you have a plugin for it. This is how most of the tools talk to jenkins.

 In this tutorial, we are going to learn a simple process to install plugins. As part of this, we will end us installing a plugin which would help us integrate jenkins with our git repository.

### Exploring Plugins Configurations
 * From "Manage Jenkins", select  "Manage Plugins" option.  
 * On the Manage Plugins pane you would see the following tabs,
   * Updates
   * Available
   * Installed
   * Advanced
   * Download progress
 ![Installed Plugins](images/plugins/installed_plugins.jpg)

 Select "Installed" to view the list of the plugins which came pre installed with jenkins.

## Checking Git Plugin
  * From "Plugin Manager", select **Installed plugins** on the left hand side.
  * You should see a search box, start typing the search term in that box. For this example, we would type **git**.

  ![Searching for Plugins](images/plugins/searching_for_plugins.jpg)

  * If you don't see Git plugin in the list, it may not have been installed at initiation - check available plugins and logs.


  ----
  :point_left:[**Prev** Chapter 2: Install Jenkins](020_install_jenkins.md)

  :point_right: [**Next** Chapter 4: Creating First Project with Jenkins](040_creating_first_job.md)
