# Eagle Libraries

This repository contains a library of electronic components for use with
[Eagle][eagle-home]. This library is developed primarily for my own projects and
might prove limited for general use. But you can of course, always use it
together with the standard Eagle library.

# Requirements

The following software must be installed on your system in order to clone and
use this library.

- [Eagle][eagle-install]
- [Git][git-install]

Depending on your needs, you might want to purchase a suitable Eagle license as
the free version in the above link offers only limited functionality.

# Usage

Carry out the following steps to set up Eagle to use this library.

- Open a terminal if you're on a Linux machine or Git Bash if you're using
  Windows. Enter the directory where you wish to clone this repository.

  ```
  cd <path>
  ```

  For example, if you wish to clone this library in your desktop folder, you
  would type one of the following commands.

  ```
  cd /home/<username>/Desktop     # Linux
  cd C:/Users/<username>/Desktop  # Windows
  ```

  Note that Git Bash uses forward slashes to separate directories in the path
  although Windows uses backslashes.

- If you are not inside another Git repository, simply clone this library by
  running the following command.

  ```
  git clone https://github.com/Kenneth-Goveas/Eagle-Libraries.git
  ```

  If, on the other hand, you wish to clone this library inside another Git
  repository, it is best to add it as a submodule.

  ```
  git submodule add https://github.com/Kenneth-Goveas/Eagle-Libraries.git
  ```

- Open Eagle and click on *Options > Directories*. Fill in the path to your
  copy of this repository into the *Libraries* field and then click *OK*. For
  example, if you cloned this library in your desktop folder, the path would be
  one of the following.

  ```
  /home/<username>/Desktop/Eagle-Libraries    # Linux
  C:\Users\<username>\Desktop\Eagle-Libraries # Windows
  ```

  Note that this time, you must use backslashes if you're on a Windows system.

If the above three steps were carried out successfully, this library should be
visible under the *Libraries* section in the Eagle control panel. Right-click on
the library and click *Use all* to instruct Eagle to include it in your project.

[eagle-home]:     https://www.autodesk.com/products/eagle
[eagle-install]:  https://www.autodesk.com/products/eagle/free-download
[git-install]:    https://git-scm.com/downloads
