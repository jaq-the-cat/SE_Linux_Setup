# Space Engineers Linux Setup Setup

Works by simply including all required Space Engineers .DLLs, setting the correct
language and framework versions and giving you a basic starting script.

Based off of [this project](https://github.com/gregretkowski/VSC-SE)
by [gregretkowski](https://github.com/gregretkowski)

## How To Use

- Install the `git` CLI tool with `sudo apt install git`
- Make your project directory with `mkdir` (e.g. `mkdir my-cool-script`)
- Enter your project with `cd` (e.g. `cd my-cool-script`)
- Clone the template with `git clone https://github.com/jaq-the-cat/SE_Linux_Setup.git`
- Enter the template project folder with `cd SE_Linux_Setup`
- Ensure you can run the initialization script with with `chmod +x init-project`
- Configure the project with `./init-project`
- Copy the necessary files to your project folder with `cp Program.cs ../` and
`cp sescript.csproj ../`
- Go back to your project folder with `cd ..`
- Remove the template folder with `rm -rf SE_Linux_Setup`
- Do some coding! The official programming guide can be found [here](https://spaceengineerswiki.com/Programming_Guide)
