# ezprez
A repo to bootstrap ezprez usage

This demo assumes you are:
1. Using GitHub
2. Using GitHub pages for deployment (see [FAQ](#faq) for setting up other deployment options)

## Setup

1. Click on "Use this template" on the [GitHub Repo](https://github.com/QU-UP/ezprez)
2. On the new repository page **MAKE SURE YOU CHECK OFF** "Include all branches"
3. Follow the steps in [usage](#usage) to begin creating your presentation locally

## Usage

Here are the steps for doing local development:

1. Install dependencies by running ```pip install ezprez``` or ```sudo pip3 install ezprez```
2. Read the usage documentation for [ezprez](https://ezprez.readthedocs.io)
3. Fill out ```example.py```; add in your ```Slide```'s and fill out TODO's
4. Push your changes and the pipeline will auto-deploy to github pages

## FAQ

<details>
 <summary>How do I preview my presentation locally?</summary>
 <p>To preview your presentation locally you need to:</p>
 <ol>
    <li>Run python example.py or python3 example.py</li>
    <li>Open /Presentation/index.html in a browser</li>
 </ol>
</details>

<details>
 <summary>How do I add in images?</summary>
 <p>There are a few steps to use images in your presentation</p>
 <ol>
    <li>Add your images to /images</li>
    <li>Use an <a href="https://ezprez.readthedocs.io/en/latest/components/#image" target="_blank">Image Component</a> that just has the filename i.e. if the image is called kieran-wood-lp-ice-caps-4k-w-peng.jpg in /images then you want to use "kieran-wood-lp-ice-caps-4k-w-peng.jpg" in the Image component</li>
 </ol>
</details>

<details>
 <summary>How do I use other hosting services?</summary>
 <p>When you run example.py the static html is exported to /Presentation so you can just deploy those files to any static file host (index.html is the whole presentation)
</details>
