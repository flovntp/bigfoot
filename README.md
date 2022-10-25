# Blackfire.io: Revealing Performance Secrets with Profiling

Well hi there! This repository holds the code and script
for the [Blackfire.io: Revealing Performance Secrets with Profiling](https://symfonycasts.com/screencast/blackfire) course on SymfonyCasts.

## Setup

If you've just downloaded the code, congratulations!!

To get it working, pour some coffee or tea, and
follow these steps:

**Install DDEV**

Please follow instructions [here](https://ddev.readthedocs.io/en/stable/)

**Start DDEV** 

```
ddev start
```

**Download Composer dependencies**

Make sure you have [Composer installed](https://getcomposer.org/download/)
and then run:

```
ddev composer install
```

**Set up the Database**

Create the database, tables, and fixtures!

```
ddev php bin/console doctrine:migrations:migrate
ddev php bin/console doctrine:fixtures:load
```

Now check out the site at `http://bigfoot.ddev.site/`

Have fun!

## Have Ideas, Feedback or an Issue?

If you have suggestions or questions, please feel free to
open an issue on this repository or comment on the course
itself. We're watching both :).

## Thanks!

And as always, thanks so much for your support and letting
us do what we love!

<3 Your friends at SymfonyCasts
