---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-messenger Astronomy led by world-wide collaborations of astronomers"
subtitle: ""
summary: ""
authors: ["admin"]
tags: []
categories: []
date: 2020-07-15T17:39:48-05:00
lastmod: 2020-07-15T17:39:48-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Multi-messenger astronomy is driven by the idea that looking at a problem from multiple perspectives yields a complete picture in a way not possible with just one method.
Astronomers have many ways in which to view the Universe: using light, like that with which we see; using charged particles, like those which allow us to use electricity; using neutrinos, nearly massless, weakly interacting particles produced in abundance by our Sun and in many astrophysical phenomena; and using gravitational waves, a consequence of gravity.
Gravitational waves are produced in all gravitational interactions involving accelerating bodies, i.e. when you walk or drive a car, or when the Earth moves around the Sun.

Scientists use these gravitational waves to study astrophysical phenomena, albeit those involving much larger bodies than you or me.
They build detectors known as interferometers to do so, which use a combination of large mirrors and powerful lasers to measure distances very accurately. 
These interferometers, with arms stretching miles in length, come in handy as gravitational waves pass, expanding and contracting space as they do so.
Presently, these detectors comprise the [Laser Interferometer Gravitational-wave Observatory (LIGO)](https://www.ligo.org), located in the United States, and [Virgo](https://www.virgo-gw.org), located in Italy, located in Italy, and they have been detecting the merger of black holes and neutron stars since 2015.
In August 2017, the detection of two neutron stars merging was captured in both gravitational waves and light, using telescopes both on the ground and in space, igniting multi-messenger astronomy as a field and revolutionizing many areas in physics and astronomy.

Since then, the third observing run (O3) of LIGO and Virgo has taken place; it began in April 2019, and was split into two parts to allow for a break to work on the interferometers: O3a (2019 April -- 2019 September) and O3b (2019 November -- 2020 March 27, ending more than a month earlier than planned because of the COVID-19 pandemic).
The scientists working on these detectors sent more than 80 public alerts to the community notifying them of these events, often within minutes of the detection.
While many of these were likely consistent with the merger of two black holes, and therefore unlikely to result in prompt emission of light, some contained at least one neutron star, and were hence more likely to have electromagnetic counterparts. Unfortunately, no electromagnetic counterparts to the events of O3 were identified, despite significant coordinated efforts by numerous observing groups. 
This is likely for a variety of reasons. The first is that the gravitational-wave detectors do not point particularly well; for many of these events, telescopes would have to cover much of the sky to have a reasonable chance of pointing at the true location of the event.
There is also the fact that not all mergers are likely to produce bright counterparts, or even ones that are detectable at all. This depends on the type and size of the compact objects involved.

Given these difficulties, it has been imperative to use multiple telescopes as part of coordinated global networks for the purpose of identifying and characterising counterparts.
This includes [GRANDMA (Global Rapid Advanced Network Devoted to the Multi-messenger Addicts)](https://grandma.lal.in2p3.fr/), and other networks such as the [Global Relay of Observatories Watching Transients Happen (GROWTH)](http://growth.caltech.edu/) and [Gravitational-wave Optical Transient Observer (GOTO)](https://goto-observatory.org/).
In addition to the telescope hardware, this campaign witnessed the emergence of many technical tools that optimize follow-up.
These tools are designed to coordinate the entire follow-up process. These pipelines automatically receive alerts from the gravitational-wave detectors and create observation plans that are then sent to the telescopes within the respective network, and also facilitate subsequent filtering/classification of incoming optical alerts from these observations.
The scheduling of observations, if it was not automated, would be a very daunting task due to the complexity of the follow-up process, which must take into account information from the GWs, the intricacies of a specific telescope, as well as various observational practicalities, such as the fact that the Sun gets in the way.
These endeavors then demonstrate the utility of developing software that deals with otherwise intractable problems to make for an overall less stress-inducing and more efficient route to discovery (or whatever outcome the fruits of one’s labor may yield).

GRANDMA and GROWTH are networks that comprise 20 and 18 observatories respectively, coordinated by teams spanning the world over.
This geographic diversity is essential to having a chance of observing a significant percentage of the GW localization in the night following the detection.
Due to factors such as portions of the sky being low on the horizon or simply behind the Sun, the possibility of observing from a certain location may be different than others, and so it is important to take this into consideration when attempting to follow-up candidate events.
For example, it is not uncommon for events to only be observable from either the Northern or the Southern Hemisphere.
These contingencies demonstrate the utility of coordinating network-level telescope observations to obtain large coverage of the localisations.

We rely on machine learning to evaluate the evolution of the amount of light and the color of the light curve to help evaluate which of the many identified transients may be the counterpart we are looking for.
We can also compare these lightcurves to models for these counterparts, and thereby rule out candidates that do not look as we might expect.
Although we did not find any viable kilonova candidates, this allowed us to set limits on what the kilonovae could have looked like, given that they must have been too faint to be present in our images.

To conclude, we highlight the important initiatives these networks are supporting.
Since the beginning of O3, GRANDMA has developed a citizen science program called kilonova-catcher.
It allows non-professional astronomers to contribute their observational capabilities to the GRANDMA network, in order to perform optical follow-up of GW candidates on a best-effort basis.
During the O3b run, 33 kilonova-catcher users around the globe registered to the GRANDMA alert stream, and the program was active during the follow-up of two merger candidates.
Because the field of view of the amateur telescopes are typically narrow, GRANDMA coordinates their observations for promising galaxies that might host the merger.
This collaboration is thus unique with this global initiative of citizen observers. In turn, the GROWTH PIRE (Partnerships for International Research and Education) program further underscores the importance of international cooperation when facing challenges that are so large and unbridled in scope, as is the case in this era of multi-messenger astronomy.
Encouraging more interaction on a global scale is a worthwhile initiative that is conducive to a better-equipped and more diverse workforce.
O3 illustrated the huge potential for multi-messenger astronomy to vitalise sky observations and counterpart candidates, while also highlighting the need for training the next generation of astronomers in this new field and supporting them to jointly analyze data from these different messengers.

You can read the papers here:
* [GRANDMA (GRANDMA Observations of Advanced LIGO's and Advanced Virgo's Third Observational Campaign)](https://arxiv.org/abs/2004.04277/)
* [GROWTH (Kilonova Luminosity Function Constraints based on Zwicky Transient Facility Searches for 13 Neutron Star Mergers
)](https://arxiv.org/abs/2006.11306/)


