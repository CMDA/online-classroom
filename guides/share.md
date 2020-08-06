# Collaborate with students

![Visual Studio Code Live Share](https://code.visualstudio.com/assets/blogs/2017/11/15/vs-code-ls-session.png)

Helping students with their code without sitting next to each other is hard. Here are some ways to do that remote.

## Video Call

This is my least favorite option but is the quickest and easiest way to help a student with code. A student does a screen share and you help them out while looking at their screen. It's cumbersome, you have to shout out line numbers, 'scroll a bit more' so not ideal.

Additionally you can ask the student to make a .zip of their code or clone it from GitHub to try to reproduce the problem on your local machine.

> Zoom supports ['Remote Control'](https://support.zoom.us/hc/en-us/articles/201362673-Requesting-or-giving-remote-control) which is a bit like teamviewer, you can access their computer and control their mouse and keyboard. It's ok, but is very laggy if their isn't a stable internet connection. When I tried it out students freak out, it's weird having an instructor control your computer.

## Code Sharing sites

A slightly better approach is have the student copy their code over to a code sharing site such as Codepen, JSfiddle or Glitch. You are sure you have the same code as the student, they can invite you to their pen or send a link so you can look at it in your browser. All benefits above downloading their code. I usually combine a video call with this method. We screen share the pen or fiddle and walk trough it.

## VSCode Live Share

Most students are using VS Code as their main editor anyway so it's nice to stay in that environment. Live Share is the perfect (and in my opinion the best out of all of the methods mentioned) way.

It's a bit of a hassle to set-up, there are a couple of steps involved but once it's installed and set-up it's smooth sailing onwards.

- Download the [Live Share Extension](https://visualstudio.microsoft.com/services/live-share/)
- Hit the Live Share button in the status bar and have the student login with a microsoft or GitHub account.
- Have the student send you the live invitation link.
- ✨ The session will automatically open in a new VSCode window.

You will now see cursors of all participants (like a google doc) and their will be a new menu called 'live share' in the explorer with more options.

The best thing is that you only share the code and related files during the session. You will still have your own VSCode workspace settings (like your color theme etc.)!

> The Audio Call feature doesn't always work for me so it's handy to have another video call (MS teams) running while you are doing this. This feature also needs a bit a stable internet connection.
