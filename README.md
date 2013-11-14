# WPTT Basic Email Logging

Contributors: Curtis McHale
Tags: wp_mail, email logging
Requires at least: 3.6
Tested up to: 3.7
Stable tag: 1.0


## Description

Basic plugin that allows you to

## Installation

1. Extract to your wp-content/mu-plugins/ folder. Create it if it doesn't exist

2. Plugin is always run and won't show up in the WordPress admin

## Usage

Use this is the mu-plugins/ folder in your WordPress site. It's meant for you to change the code. Define your live, local, and staging site url's as needed.

You can then use them in any plugin since they are defined before regular plugins are loaded. It lets you do stuff like configure email logging on all staging and local sites by checking the defined constants.

## Changelog

### 1.0

- basic constants configuration