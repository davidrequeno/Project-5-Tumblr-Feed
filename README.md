Project 5 – Tumblr Feed
Submitted by: David Requeno

Tumblr Feed is an app that fetches and displays photo post. The app loads posts from the Tumblr API, shows each post’s image and summary, and presents them in a scrollable table view.

Time spent: 1:30 
Required Features
The following required functionality is completed:

[x] App has a configured table view and custom table view cell

[x] App populates the table view with data fetched from the Tumblr API

[x] App displays post images and summaries

[x] App loads images asynchronously using NukeExtensions

Optional Features
The following optional features are implemented:

[x] App fetches posts from a different Tumblr blog (HONY)

[x] App includes a refresh control to reload posts

Video Walkthrough

[
](https://www.loom.com/share/4769bdb5397a49f5a16fdd9a4d6fddd6)

Notes

The main challenges were wiring the storyboard correctly, connecting outlets, and ensuring the JSON decoding matched Tumblr’s nested API structure. Once the models and cell were set up, the rest of the project came together smoothly.


License

    Copyright 2026 David Requeno

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
