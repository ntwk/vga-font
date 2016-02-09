# VGA Fonts

A few Linux console fonts converted for use under X11

## Overview

These fonts are BDF conversions of some console fonts originally
distributed as part of the kbd package.  The kbd package is, itself, a
part of many Linux distributions.  These BDF conversions allow you to
use these same console fonts in your X11 applications.

## Installation

1. Copy or symlink the fonts to your ~/.fonts directory:
   `cp Uni-VGA*.bdf ~/.fonts`
2. Run `fc-cache -fv` to update your font cache.
