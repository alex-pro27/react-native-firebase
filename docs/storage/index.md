---
title: Cloud Storage
description: Cloud Storage for Firebase is a powerful, simple, and cost-effective object storage service built for Google scale
---

# Cloud Storage

React Native Firebase provides native integration with Cloud Storage, providing support to upload and download files
directly from your device and from your Firebase Cloud Storage bucket.

<Youtube id="_tyjqozrEPY" />

## Getting Started

<Grid columns="3">
	<Block
		icon="cloud_queue"
		color="#ffc107"
		title="Quick Start"
		to="/quick-start"
	>
    Install & manage your files with your Firebase storage bucket.
	</Block>
	<Block
		icon="school"
		color="#4CAF50"
		title="Guides"
		version={false}
		to="/guides?tags=storage"
	>
	  TODO
	</Block>
  <Block
		icon="layers"
		color="#03A9F4"
		title="Reference"
		to="/reference"
	>
    The API reference covers everything required to successfully integrate Cloud Storage with your application.
	</Block>
</Grid>

## Errors
The functions in this module can throw two different types of errors. If ill-formed urls are passed into them, they will throw
[generic Errors](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error) with messages 
explaining the problem that caused them.

If error was thrown by Firebase itself, then the function will throw a [NativeFirebaseError](https://invertase.io/oss/react-native-firebase/v6/app/reference/nativefirebaseerror). The codes for these errors are the same as the codes for [Firebase Cloud Storage Web errors](https://firebase.google.com/docs/storage/web/handle-errors).


## Learn more

Our documentation is a great place to start, however if you're looking for more help or want to help others,
check out the resources below:

- [Stack Overflow](https://stackoverflow.com/questions/tagged/react-native-firebase-storage)
- [Github Issues](https://github.com/invertase/react-native-firebase/labels/Service%3A%20Storage)
- [Firebase Documentation](https://firebase.google.com/docs/storage?utm_source=invertase&utm_medium=react-native-firebase&utm_campaign=storage)
