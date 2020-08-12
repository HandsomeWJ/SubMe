# SubMe 

A cloud deployment of ![Autosub](https://github.com/BingLingGroup/autosub) on Google Colab. It leverages Google's computing power and GPU to automatically generate subtitles for uploaded video files in various languages. Audio is first pre-processed using `ffmpeg` and `ffmpeg-normalize`. Speech recognition is then conducted on the pre-processed audio using `Auditok`, after which `ffmpeg` will be used to splice the audio files into individual segments. The segments will be transcribed using Google's Cloud Speech-to-Text API, then translated into your desired language using `py-googletrans`. Additionally, there is also a feature which allows you to leverage Google's cloud computing clusters to download torrents via magnets over a peer-to-peer connection. 

Our tool significantly speeds up the runtime of Autosub. As a free service, the GPU-enabled Google Colab environment (which is what we are using now) is significantly faster than a GPU-enabled MacBook Pro, Lenovo Legion and Lenovo Thinkpad, contributing to greater time savings. Furthermore, without the need to provision and maintain expensive hardware, users will also enjoy greater cost savings. Moreover, our tool will also help the less fortunate, such as those with hearing disabilities, to decipher what is being spoken in videos and movies. 
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc


