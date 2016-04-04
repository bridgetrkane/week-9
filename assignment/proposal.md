# Final Project Proposal

Detailed proposal for my final project.

## Problem / Question

My application hopes to improve health and wellness by addressing access to
nature in San Francisco and surrounding areas. San Francisco is a beautiful
city, and has access to a variety of parks and protected environmental areas.
I'm hoping to create an app that showcases the accessibility of these areas,
helping residents to gain more exposure to nature on a daily basis.

## The data

Using data from the SF OpenData site, including park lands polygons and
protected areas, I hope to layer said locations with data relating to
playgrounds, dog parks/runs, picnic tables, gardens, urban tree canopy, etc.
Most of this data is already stored as JSON or csv, and I will convert these to
GeoJSON.

## Technologies used

I will likely be using underscore.js, jQuery, bootstrap, and D3 for this
assignment. With underscore and jQuery, people will be able to find nearby
parks, etc., by entering a certain address that will be geocoded to reveal
nearby points of interest. I'd like to use D3 in some way to visualize access
in an interesting way. Much of this will be determined as I begin to work
through my dad to see what will be most useful & engaging for the user.

## Design spec

#### User experience

Although a similar application already exists (via the city of SF), I hope to
make my app more intuitive for the user. What I mean by that is that it will be
easy to explore the data via mouse-over popups and easy access to pictures
associate with different locations, so that the user does not need to do much
additional research. As such, this will be more of a "one stop shop" for parks
and outdoor activities in SF, which is what makes it more appealing than other,
or more traditional, apps of its kind.

#### Layouts and visual design

I'd like to use a top bar for this assignment, because I feel that this layout
is a bit more inviting. This also leaves room for me to provide a lot of
data about each location. Information about the specific location type
(i.e. hiking trail, dog park, swimming, etc.) could then be displayed along the
bottom, while associated pictures could be displayed on the map itself on
clicking. To make it a bit easier to explore locations, I will provide general
information, such as name and category, in a mouse-over popup.

## Anticipated difficulties

I think that one of the most difficult things about this project will be
incorporating/associating/retrieving pictures and images with each location.
That said, this is an important part of what makes this application interesting.
I will have to find a successful way to do this while making sure that the
overall style remains intuitive and doesn't get too bogged down with information
and features.

## Missing pieces

D3 seems exciting to me in terms of engaging visualizations, and I hope to be
able to use this in some manner for my application, though I'm not certain
where it could fit just yet.
