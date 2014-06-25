sinatra-hello-world
===================

This is a example Ruby application that can be deployed to [Qt Cloud Services](https://www.qtcloudservices.com)

## Getting Started with Managed Application Runtime
Before running through the Managed Application Runtime (**"MAR"**) getting started guide, please make sure that you can access the [management console](https://console.qtcloudservices.com). You will need a valid Qt Account or a Github account to access the management console.

## Setting Up Your First MAR Instance
This section will describe how to start your first MAR instance. If you are using the Qt Cloud Services management console for the first time, you will need to create a **cloud** before you can start your MAR instance. You can create a cloud easily by using the **"Quick Start"** wizard.

It is easy to start your MAR instance. Simply follow the steps below:

1. Select the cloud you want to start your MAR instance.
2. Once the cloud is selected, click "**Launch Instance**" under the Managed Application Runtime section of the management console.
3. Enter the name for your MAR instance.
4. Select the runtime size. Runtime size will determine how much memory and CPU will be allocated for your instance. For now, just pick "**ar-1-mini**".
5. Select the runtime type. It will define how the instance will be used. Since in this getting started guide we will be writing a simple application, choose "**Application**".
6. Once the Managed Application Runtime settings are in place, click "**Create**".

## Setting Up Your SSH Keys
Once you have created your first MAR instance, you'll need to [set up your personal SSH keys](https://developer.qtcloudservices.com/mar/key-concepts/personal-ssh-keys). SSH keys are used to authenticate your access to MAR instances when deploying code or opening remote access connections to database instances.

## Making Your First Application
Clone / fork this repo to your local computer.

**NOTE!** Please test the application on your local computer before proceeding to the next step!

## Deploy To Managed Application Runtime
You can deploy application with command 
```
git push runtime master
```
## Next Steps
You are now ready to learn more about the [Key Concepts](https://developer.qtcloudservices.com/mar/key-concepts) of MAR. We hope you will find this documentation helpful!
