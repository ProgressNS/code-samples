# Contributing a NativeScript Code Sample

Interested in contributing your own sample app? Awesome! 👍

Before you submit anything, here are some guidelines we'd like you to follow:

 - [Code of Conduct](#coc)
 - [Signing the CLA](#cla)
 - [Submission Guidelines](#submit)

## <a name="coc"></a> Code of Conduct

Please be aware of, and follow, our official [Code of Conduct](https://github.com/NativeScript/codeofconduct).

## <a name="cla"></a> Signing the CLA

Please sign our [Contributor License Agreement](http://www.nativescript.org/cla) (CLA) before sending pull requests. For any code changes to be accepted, the CLA must be signed. It's easy, we promise! 😀

## <a name="submit"></a> Submission Guidelines

The entire data source for the code samples lives in a monolithic `data/all.json` file in this repository. Any PR you make must conform to the structure of the individual code samples provided in there.

> When in doubt, just submit a PR with a link to your NativeScript Playground project. We can help you fill in the details! 😀

For example:

	{
		"name": "Building a Good-Looking Login Form",
		"description": "A good looking login/registration experience is a must have for any app. Here is a simple yet elegant looking login form example.",
		"screenshots": [
			"https://raw.githubusercontent.com/NativeScript/code-samples/master/screens/login-form-ios-1.png",
			"https://raw.githubusercontent.com/NativeScript/code-samples/master/screens/login-form-android-1.png"
		],
		"links": {
			"angular": "https://play.nativescript.org/?template=play-ng&id=Hqp5UQ&v=29",
			"vue": "https://play.nativescript.org/?template=play-vue&id=HdDm9M&v=2",
			"core": "https://play.nativescript.org/?template=play-js&id=h9CNcL&v=3"
		},
		"categories": [
			"layouts and pages"
		],
		"authors": [
			{
				"name": "TJ VanToll",
				"npmuser": "tjvantoll",
				"framework": "angular"
			},
			{
				"name": "Igor Randjelovic",
				"npmuser": "rigor789",
				"framework": "vue"
			},
			{
				"name": "Shiva Prasad",
				"npmuser": "multishiv19",
				"framework": "core"
			}
		],
		"readme": "",
		"keywords": [
			"login",
			"form",
			"sign up",
			"password"
		]
	}

- **Name:** A short name of the app.
- **Description:** A longer description, no more than two concise sentences.
- **Screenshots:** At least one screenshot (two screenshots if platform differences are significant). **Must have consistent height of 1080px!** Ideally your png or jpg screenshots will be compressed with a services like [TinyPNG](https://tinypng.com/).
- **Links:** URL(s) to the NativeScript Playground instance(s). Leave an empty string for any missing frameworks. **URLs should end with `v=` which signifies that you have saved the Playground project at least once.**
- **Categories:** Enter an array of one or more categories from the [README](readme.md) doc.
- **Authors:** The authors of the associated Playground links.
- **ReadMe:** Not currently used.
- **Keywords:** Optional keywords to make your code sample more easily discoverable.

That's it! Thank you for your contribution! 🤗