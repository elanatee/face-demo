# face

this project demonstrates how to use the [Microsoft Cognitive Services](https://www.microsoft.com/cognitive-services/) [Face API](https://www.microsoft.com/cognitive-services/en-us/face-api) for facial recognition.

## prerequisites 
- a text editor of your choice (sublime text, atom, xcode, etc.)
- [Python](https://www.python.org/downloads/)
- pip package installer (`sudo easy_install pip`)
- [Microsoft Azure](https://azure.microsoft.com) subscription 

## setup 
- open terminal or command prompt

- clone this repository (or download it to your desktop):

```bash
$ git clone https://github.com/elanatee/cognitive-services-demo.git
```

- navigate to the directory: 

```bash
$ cd /path/to/cognitive-services-demo-master
```

- set up a virtual environment
   - [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/) is used to create isolated Python environments - using virtualenv makes it so that the dependencies of your different projects are maintained in different places. install virtualenv on your machine:
    ```bash
    $ pip install virtualenv
    ```
   - in the project directory, create and activate the virtual environment for your project
    ```bash
    $ virtualenv venv
    $ . venv/bin/activate
    ```
   use `deactivate` to exit the virtual environment

- set up the project to work with your API key
   1. get your Face API subscription key [here](https://www.microsoft.com/cognitive-services/en-US/subscriptions)
   2. open the file `keys.py` in a text editor
   3. copy/paste your key into the single quotes 
   4. save the file

- now you can open terminal or command prompt, and run your program! 
```bash
$ python app.py
```

## resources & further reading 
- [Face API Documentation](https://www.microsoft.com/cognitive-services/en-us/face-api/documentation/overview)
   - [How to Detect Faces in an Image](https://www.microsoft.com/cognitive-services/en-us/face-api/documentation/face-api-how-to-topics/HowtoDetectFacesinImage) 
- [Face API Reference](https://westus.dev.cognitive.microsoft.com/docs/services/563879b61984550e40cbbe8d/operations/563879b61984550f30395236) 
- [A Beginners Guide to Cognitive Services](https://www.linkedin.com/pulse/idiots-guide-cognitive-services-nigel-willson) by Nige Willson
- [Getting to Know the Command Line](https://www.davidbaumgold.com/tutorials/command-line/) by David Baumgold

### thanks for reading!
feedback and pull requests are warmly welcomed and encouraged! 

feel free to tweet me [@elanatee](https://twitter.com/elanatee) or email me at etee (at) fordham (dot) edu if you have any questions!