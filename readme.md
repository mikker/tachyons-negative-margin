# tachyons-negative-margin 1.0.0

Performance based css module.

#### Stats

1220 | 196 | 252
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-negative-margin
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-negative-margin
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-negative-margin.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-negative-margin";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://npmcdn.com/tachyons-negative-margin@1.0.0/css/tachyons-negative-margin.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-negative-margin">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/* Variables */
/* Spacing Scale - based on a ratio of 1:2 */
/* Media Queries */
/*
   SPACING

   An eight step powers of two scale ranging from 0 to 16rem.
   Namespaces are composable and thus highly grockable - check the legend below

   Legend:

   p = padding
   m = margin

   a = all
   h = horizontal
   v = vertical
   t = top
   r = right
   b = bottom
   l = left

   1 = 1st step in spacing scale
   2 = 2nd step in spacing scale
   3 = 3rd step in spacing scale
   4 = 4th step in spacing scale
   5 = 5th step in spacing scale
   6 = 6th step in spacing scale
   7 = 7th step in spacing scale

*/
.man1 { margin: -.25rem; }
.man2 { margin: -.5rem; }
.man3 { margin: -1rem; }
.man4 { margin: -2rem; }
.man5 { margin: -4rem; }
.man6 { margin: -8rem; }
.man7 { margin: -16rem; }
.mln1 { margin-left: -.25rem; }
.mln2 { margin-left: -.5rem; }
.mln3 { margin-left: -1rem; }
.mln4 { margin-left: -2rem; }
.mln5 { margin-left: -4rem; }
.mln6 { margin-left: -8rem; }
.mln7 { margin-left: -16rem; }
.mrn1 { margin-right: -.25rem; }
.mrn2 { margin-right: -.5rem; }
.mrn3 { margin-right: -1rem; }
.mrn4 { margin-right: -2rem; }
.mrn5 { margin-right: -4rem; }
.mrn6 { margin-right: -8rem; }
.mrn7 { margin-right: -16rem; }
.mbn1 { margin-bottom: -.25rem; }
.mbn2 { margin-bottom: -.5rem; }
.mbn3 { margin-bottom: -1rem; }
.mbn4 { margin-bottom: -2rem; }
.mbn5 { margin-bottom: -4rem; }
.mbn6 { margin-bottom: -8rem; }
.mbn7 { margin-bottom: -16rem; }
.mtn1 { margin-top: -.25rem; }
.mtn2 { margin-top: -.5rem; }
.mtn3 { margin-top: -1rem; }
.mtn4 { margin-top: -2rem; }
.mtn5 { margin-top: -4rem; }
.mtn6 { margin-top: -8rem; }
.mtn7 { margin-top: -16rem; }
.mv1 { margin-top: .25rem; margin-bottom: .25rem; }
.mv2 { margin-top: .5rem; margin-bottom: .5rem; }
.mv3 { margin-top: 1rem; margin-bottom: 1rem; }
.mv4 { margin-top: 2rem; margin-bottom: 2rem; }
.mv5 { margin-top: 4rem; margin-bottom: 4rem; }
.mv6 { margin-top: 8rem; margin-bottom: 8rem; }
.mv7 { margin-top: 16rem; margin-bottom: 16rem; }
.mhn1 { margin-left: -.25rem; margin-right: -.25rem; }
.mhn2 { margin-left: -.5rem; margin-right: -.5rem; }
.mhn3 { margin-left: -1rem; margin-right: -1rem; }
.mhn4 { margin-left: -2rem; margin-right: -2rem; }
.mhn5 { margin-left: -4rem; margin-right: -4rem; }
.mhn6 { margin-left: -8rem; margin-right: -8rem; }
.mhn7 { margin-left: -16rem; margin-right: -16rem; }
@media screen and (min-width: 30em) {
 .man1-ns { margin: -.25rem; }
 .man2-ns { margin: -.5rem; }
 .man3-ns { margin: -1rem; }
 .man4-ns { margin: -2rem; }
 .man5-ns { margin: -4rem; }
 .man6-ns { margin: -8rem; }
 .man7-ns { margin: -16rem; }
 .mln1-ns { margin-left: -.25rem; }
 .mln2-ns { margin-left: -.5rem; }
 .mln3-ns { margin-left: -1rem; }
 .mln4-ns { margin-left: -2rem; }
 .mln5-ns { margin-left: -4rem; }
 .mln6-ns { margin-left: -8rem; }
 .mln7-ns { margin-left: -16rem; }
 .mrn1-ns { margin-right: -.25rem; }
 .mrn2-ns { margin-right: -.5rem; }
 .mrn3-ns { margin-right: -1rem; }
 .mrn4-ns { margin-right: -2rem; }
 .mrn5-ns { margin-right: -4rem; }
 .mrn6-ns { margin-right: -8rem; }
 .mrn7-ns { margin-right: -16rem; }
 .mbn1-ns { margin-bottom: -.25rem; }
 .mbn2-ns { margin-bottom: -.5rem; }
 .mbn3-ns { margin-bottom: -1rem; }
 .mbn4-ns { margin-bottom: -2rem; }
 .mbn5-ns { margin-bottom: -4rem; }
 .mbn6-ns { margin-bottom: -8rem; }
 .mbn7-ns { margin-bottom: -16rem; }
 .mtn1-ns { margin-top: -.25rem; }
 .mtn2-ns { margin-top: -.5rem; }
 .mtn3-ns { margin-top: -1rem; }
 .mtn4-ns { margin-top: -2rem; }
 .mtn5-ns { margin-top: -4rem; }
 .mtn6-ns { margin-top: -8rem; }
 .mtn7-ns { margin-top: -16rem; }
 .mvn1-ns { margin-top: -.25rem; margin-bottom: -.25rem; }
 .mvn2-ns { margin-top: -.5rem; margin-bottom: -.5rem; }
 .mvn3-ns { margin-top: -1rem; margin-bottom: -1rem; }
 .mvn4-ns { margin-top: -2rem; margin-bottom: -2rem; }
 .mvn5-ns { margin-top: -4rem; margin-bottom: -4rem; }
 .mvn6-ns { margin-top: -8rem; margin-bottom: -8rem; }
 .mvn7-ns { margin-top: -16rem; margin-bottom: -16rem; }
 .mhn1-ns { margin-left: -.25rem; margin-right: -.25rem; }
 .mhn2-ns { margin-left: -.5rem; margin-right: -.5rem; }
 .mhn3-ns { margin-left: -1rem; margin-right: -1rem; }
 .mhn4-ns { margin-left: -2rem; margin-right: -2rem; }
 .mhn5-ns { margin-left: -4rem; margin-right: -4rem; }
 .mhn6-ns { margin-left: -8rem; margin-right: -8rem; }
 .mhn7-ns { margin-left: -16rem; margin-right: -16rem; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .man1-m { margin: -.25rem; }
 .man2-m { margin: -.5rem; }
 .man3-m { margin: -1rem; }
 .man4-m { margin: -2rem; }
 .man5-m { margin: -4rem; }
 .man6-m { margin: -8rem; }
 .man7-m { margin: -16rem; }
 .mln1-m { margin-left: -.25rem; }
 .mln2-m { margin-left: -.5rem; }
 .mln3-m { margin-left: -1rem; }
 .mln4-m { margin-left: -2rem; }
 .mln5-m { margin-left: -4rem; }
 .mln6-m { margin-left: -8rem; }
 .mln7-m { margin-left: -16rem; }
 .mrn1-m { margin-right: -.25rem; }
 .mrn2-m { margin-right: -.5rem; }
 .mrn3-m { margin-right: -1rem; }
 .mrn4-m { margin-right: -2rem; }
 .mrn5-m { margin-right: -4rem; }
 .mrn6-m { margin-right: -8rem; }
 .mrn7-m { margin-right: -16rem; }
 .mbn1-m { margin-bottom: -.25rem; }
 .mbn2-m { margin-bottom: -.5rem; }
 .mbn3-m { margin-bottom: -1rem; }
 .mbn4-m { margin-bottom: -2rem; }
 .mbn5-m { margin-bottom: -4rem; }
 .mbn6-m { margin-bottom: -8rem; }
 .mbn7-m { margin-bottom: -16rem; }
 .mtn1-m { margin-top: -.25rem; }
 .mtn2-m { margin-top: -.5rem; }
 .mtn3-m { margin-top: -1rem; }
 .mtn4-m { margin-top: -2rem; }
 .mtn5-m { margin-top: -4rem; }
 .mtn6-m { margin-top: -8rem; }
 .mtn7-m { margin-top: -16rem; }
 .mvn1-m { margin-top: -.25rem; margin-bottom: -.25rem; }
 .mvn2-m { margin-top: -.5rem; margin-bottom: -.5rem; }
 .mvn3-m { margin-top: -1rem; margin-bottom: -1rem; }
 .mvn4-m { margin-top: -2rem; margin-bottom: -2rem; }
 .mvn5-m { margin-top: -4rem; margin-bottom: -4rem; }
 .mvn6-m { margin-top: -8rem; margin-bottom: -8rem; }
 .mvn7-m { margin-top: -16rem; margin-bottom: -16rem; }
 .mhn1-m { margin-left: -.25rem; margin-right: -.25rem; }
 .mhn2-m { margin-left: -.5rem; margin-right: -.5rem; }
 .mhn3-m { margin-left: -1rem; margin-right: -1rem; }
 .mhn4-m { margin-left: -2rem; margin-right: -2rem; }
 .mhn5-m { margin-left: -4rem; margin-right: -4rem; }
 .mhn6-m { margin-left: -8rem; margin-right: -8rem; }
 .mhn7-m { margin-left: -16rem; margin-right: -16rem; }
}
@media screen and (min-width: 60em) {
 .man1-l { margin: -.25rem; }
 .man2-l { margin: -.5rem; }
 .man3-l { margin: -1rem; }
 .man4-l { margin: -2rem; }
 .man5-l { margin: -4rem; }
 .man6-l { margin: -8rem; }
 .man7-l { margin: -16rem; }
 .mln1-l { margin-left: -.25rem; }
 .mln2-l { margin-left: -.5rem; }
 .mln3-l { margin-left: -1rem; }
 .mln4-l { margin-left: -2rem; }
 .mln5-l { margin-left: -4rem; }
 .mln6-l { margin-left: -8rem; }
 .mln7-l { margin-left: -16rem; }
 .mrn1-l { margin-right: -.25rem; }
 .mrn2-l { margin-right: -.5rem; }
 .mrn3-l { margin-right: -1rem; }
 .mrn4-l { margin-right: -2rem; }
 .mrn5-l { margin-right: -4rem; }
 .mrn6-l { margin-right: -8rem; }
 .mrn7-l { margin-right: -16rem; }
 .mbn1-l { margin-bottom: -.25rem; }
 .mbn2-l { margin-bottom: -.5rem; }
 .mbn3-l { margin-bottom: -1rem; }
 .mbn4-l { margin-bottom: -2rem; }
 .mbn5-l { margin-bottom: -4rem; }
 .mbn6-l { margin-bottom: -8rem; }
 .mbn7-l { margin-bottom: -16rem; }
 .mtn1-l { margin-top: -.25rem; }
 .mtn2-l { margin-top: -.5rem; }
 .mtn3-l { margin-top: -1rem; }
 .mtn4-l { margin-top: -2rem; }
 .mtn5-l { margin-top: -4rem; }
 .mtn6-l { margin-top: -8rem; }
 .mtn7-l { margin-top: -16rem; }
 .mvn1-l { margin-top: -.25rem; margin-bottom: -.25rem; }
 .mvn2-l { margin-top: -.5rem; margin-bottom: -.5rem; }
 .mvn3-l { margin-top: -1rem; margin-bottom: -1rem; }
 .mvn4-l { margin-top: -2rem; margin-bottom: -2rem; }
 .mvn5-l { margin-top: -4rem; margin-bottom: -4rem; }
 .mvn6-l { margin-top: -8rem; margin-bottom: -8rem; }
 .mvn7-l { margin-top: -16rem; margin-bottom: -16rem; }
 .mhn1-l { margin-left: -.25rem; margin-right: -.25rem; }
 .mhn2-l { margin-left: -.5rem; margin-right: -.5rem; }
 .mhn3-l { margin-left: -1rem; margin-right: -1rem; }
 .mhn4-l { margin-left: -2rem; margin-right: -2rem; }
 .mhn5-l { margin-left: -4rem; margin-right: -4rem; }
 .mhn6-l { margin-left: -8rem; margin-right: -8rem; }
 .mhn7-l { margin-left: -16rem; margin-right: -16rem; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

