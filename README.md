# Lux for Windows

Compiled download only. The source lives in a private repository.

## Install

Open PowerShell and paste one line:

    irm https://github.com/GuruProduction/lux-releases/releases/latest/download/install.ps1 | iex

Then close that window, open a new PowerShell, and type:

    lux

The first time, sign in with:

    /login

Choose "Staff instance" and use your Unus Lumen email and password. That is the
only time you sign in.

## What this is

A single compiled application. No source code, no bun, no database setup, no
environment files. Prompts, tools, skills, agents and the model all come from
the Unus Lumen panel after you sign in.

Signing in is the only way to use it. Until you do, the application starts and
tells you to run /login; no model call can run without a credential.
