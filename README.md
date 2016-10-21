# Item Catalog
###### Udacity's Full Stack Web Developer Nanodegree
----


Develop an application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.


## Files
| File | Description |
|------|-------------|
| **database_setup.py**  | This file is used to provide access to your database tables.  |
| **lotsofmenus.py** | This file is used to provide dummy user information. |
| **project.py** | This file provides all the user authentication, routes, views, and actions.  |




## Installation And Usage:
#### Prerequisites:

| Program | Download |
|---------------|----------|
| **Virtual Box** | [download](https://www.virtualbox.org/wiki/Downloads)|
| **Vagrant** |  [download](https://www.vagrantup.com/downloads)       |
| **Facebook Developer** | [Click Here](https://developers.facebook.com/) |

1. Create a Facebook App ID through their website.
2. Open terminal
    - Run: `$ git clone https://github.com/egarcia410/Item-Catalog.git`
3. Using a text editor, update App ID and App Secret
    - Update: template **login.html** line #72 with App ID
    - Update: **fb_client_secrets.json** with App ID and App Secret
    - Save Changes
4. Move to the *vagrant* folder by entering:
    - `$ cd Item-Catalog/vagrant/`
5. Run Vagrant by entering:
    - Run: ` $ vagrant up`
    - In less than a minute, this command will finish and you will have a virtual machine running Ubuntu.
6. SSH into the machine:
    - Run: `$ vagrant ssh`
    - This command will drop you into a full-fledged SSH session.
7. Move to the *catalog* folder  by entering:
    - Run: `$ cd /vagrant/catalog`
8. `$ python lotsofmenus.py`
9. `$ python project.py`
10. Navigate to http://localhost:5000/ in web browser.



## License
Licensed under the MIT License (MIT)

```
Copyright (c) [2016] [Emmanuel Garcia]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```



