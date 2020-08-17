# PGAcloud
Bachelor's Thesis on a Cloud Framework for Polyglot PGA deployment.
This is an umbrella repository containing all components of our framework.

For details on a particular component, refer to the corresponding README file located in the component's repository.

If this will still not answer the questions, please refer to the Bachelor thesis document on the PGAcloud framework:
"A Cloud Framework for Polyglot Parallel Genetic Algorithms". 


## Usage
Download the *Client* repository and save it on your machine.
In a terminal or shell window, navigate to the *Client* repository.
To enable the *Client*'s command-line interface, enter the following command: `. venv/Scripts/activate`

You should see `(venv)` being displayed above the command prompt if successful.
The *Client* commands are now ready for usage.

If you are not yet familiar with the command structure,
enter `client cloud --help` for cloud related commands,
or `client pga --help` for PGA related commands.  
For convenience, your interactions with the *Client* maintain a context file to store non-retrievable
information you entered while using the provided commands.
You can display or change these configurations, see `client config --help` for more details.


### Git Submodules
Some information for the *PGAcloud* developers regarding git submodules:\
This umbrella repository only points to a specific commit of the submodules.
If you commit any changes to a submodule, the umbrella repository will NOT automatically contain these changes.
To check for updates to the respective submodules, you can run the following command:\
`git submodule update --remote --merge`

Here are two useful links to familiarize yourself with git submodules:
- https://dev.to/milu_franz/git-explained-an-umbrella-structure-using-git-submodules-20dl
- https://git-scm.com/book/en/v2/Git-Tools-Submodules


## License
*PGAcloud* is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).
Please see the [LICENSE](LICENSE.md) file for full details.
