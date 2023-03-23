Original App Design Project - README Template
===

# PlatePal

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
This application will allow the users to 

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Recipe and Diet app
- **Mobile:** The app will have a responsive layout for all mobile phones.
- **Story:** The app is not overly complicated allowing a good user experience
- **Market:** People interested in nutrition or cooking
- **Habit:** The user interface would be easy to access. User may be able to track recipies
- **Scope:** 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* #1 Diet Selection: User should be able to select a diet type.
* #2 Recipe List: User should see a list of recipes for the current diet.
* #3 Recipe Steps:User should see a step by step process of the recipe.

**Optional Nice-to-have Stories**

* Users should be able to log in their accounts.
* Users should be able to like recipes and save them for easy access.

### 2. Screen Archetypes

* Diet selection screen
   * #1 Diet Selection
* Recipe list screen
   * #2 Recipe List
* Recipe detail screen
   * #2 Recipe Steps

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Diets Tab
* Recipes Tab

**Flow Navigation** (Screen to Screen)

* Diets 
   * Recipes list for that diet
* Recipes list
   * Recipe details/steps for respective recipe

## Wireframes
<img src="https://i.imgur.com/99pPXe4.jpeg" width=600>

## Schema 
[This section will be completed in Unit 9]
### Models
User:
username
password
profileImage
email

Recipe:
title
dietType
recipeDescription
recipeSteps
recipeImage

Diet:
name
description
recipeList

### Networking
- Diets Screen: Spoonacular API
- Recipes Screen: Spoonacular API
