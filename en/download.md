---
layout: default
title: Download Mu
i18n: en
---

# Download Mu

There are many ways to install Mu. The simplest is to download the official
installer for Windows or Mac OSX. If you're a more advanced user you can use
Python's built-in `pip` tool. Some Linux distributions come with Mu packaged
already (and you should use your OS's package manager to install it). Finally,
if you're on Raspbian (the version of Linux for Raspberry Pi) you can install
Mu as a package.

Each option is outlined below:


<div class="row">
  <div class="col-sm-6 col-md-3">
    <div class="thumbnail">
      <img src="/img/windows_logo.png" alt="Windows Logo">
      <div class="caption">
        <h3>Windows Installer</h3>
        <p><a href="https://github.com/mu-editor/mu/releases/download/v1.0.0/mu-editor_1.0_win32.exe" class="btn btn-primary" role="button">32-bit</a>
        <a href="https://github.com/mu-editor/mu/releases/download/v1.0.0/mu-editor_1.0_win64.exe" class="btn btn-primary" role="button">64-bit</a>
        <a href="/en/howto/install_windows" class="btn btn-default" role="button">Instructions</a></p>
      </div>
    </div>
  </div>
  <div class="col-sm-6 col-md-3">
    <div class="thumbnail">
      <img src="/img/apple_logo.png" alt="Apple Logo">
      <div class="caption">
        <h3>Mac OSX Installer</h3>
        <p><a href="https://github.com/mu-editor/mu/releases/download/v1.0.0/mu-editor_1.0_osx.dmg" class="btn btn-primary" role="button">Download</a>
        <a href="/en/howto/install_macos" class="btn btn-default" role="button">Instructions</a></p>
      </div>
    </div>
  </div>
  <div class="col-sm-6 col-md-3">
    <div class="thumbnail">
      <img src="/img/python_logo.png" alt="Python Logo">
      <div class="caption">
        <h3>Python Package</h3>
        <p><a href="/en/howto/install_with_python" class="btn btn-default" role="button">Instructions</a></p>
      </div>
    </div>
  </div>
  <div class="col-sm-6 col-md-3">
    <div class="thumbnail">
      <img src="/img/rpi_logo.png" alt="Raspberry Pi Logo">
      <div class="caption">
        <h3>Raspbian</h3>
        <p><a href="/en/howto/install_raspberry_pi" class="btn btn-default" role="button">Instructions</a></p>
      </div>
    </div>
  </div>
</div>

<div class="panel panel-danger">
    <div class="panel-heading"><h3 class="panel-title">ATTENTION LINUX USERS!</h3></div>
    <div class="panel-body">
    <p>On Linux, in order for Mu to work with the MicroPython based devices
    you need to ensure you add yourself to the correct permissions group
    (usually the <code>dialout</code> or <code>uucp</code> groups). Also make
    sure that your distribution automatically mounts flash devices, or make
    sure to mount them manually.</p>
    </div>
</div>
