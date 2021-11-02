# Smooch

Smooch is a brushy handwritten script font full of speedy personality. It has a contemporary feel often accomplished with stranded brush strokes. 

It is slightly bolder than other hand-lettered scripts by its creator and has up to five stylistic sets as well as initial and final positional forms expanding its utility. 

![Sample Image](Documentation/image1.png)

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
