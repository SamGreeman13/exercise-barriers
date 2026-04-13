# What Barriers Are Keeping People from Physical Activity?

An interactive visualization project exploring the gap between perceived and actual barriers to physical activity among Boston-area residents.

## Overview

Boston ranks among the most fitness-friendly cities in the country, with roughly 21 gyms per 100,000 residents and abundant walkable outdoor spaces. Yet many residents still feel fitness isn't accessible. This project investigates why — combining qualitative interview data with quantitative spatial and physiological analysis to surface the barriers people face.

A central finding drives the design: a **"barrier gap"** between what participants *say* stops them (time, cost) and what *actually* weighs on them most (body image, social media influence, gym intimidation). All three visualizations are designed to make this gap visible.

## Visualizations

### Venn Diagram Landing Page — `index.html`
An interactive Venn diagram organizing barriers into three categories: **Mental Capacity**, **Time**, and **Accessibility/Distance**. Hovering over each region previews the linked visualization; clicking navigates to it. Features a parallax equipment background, geometric distance-based hit detection for circular click zones, and SVG gym equipment shapes.

### Daily Energy Distribution — `energy_timeline_v5.html`
A MET-hours accumulation chart that lets users adjust how they spend their day and see whether their energy budget has room for exercise. Users set hours per activity via sliders, and the chart stacks activities left to right showing cumulative energy expenditure against a configurable daily ceiling. Includes sort buttons (MET-hours / Hours / METs), a "Can you fit a workout?" verdict panel, and an expandable explainer on how METs work.

### Self-Assessment & Recommendations — `self_assessment.html`
A radar chart where users rate themselves on five psychological dimensions (gym intimidation, social media impact, gym confidence, fear of judgment, need for a partner). The user's profile (dark) is overlaid against the average of all eight interview participants (pink). Clicking any point on the radar reveals evidence-based recommendations drawn from how participants with similar barriers overcame them.

### Gym Accessibility Map — `boston_gym_map_v4.html`
An isochrone-based map showing gym accessibility across Boston by walking and transit time. Generated from `isochrone_v4.ipynb` using the MBTA V3 API (chosen over MassGIS to include Green Line Extension data).

## Authors

Téa Adams · Sam Greeman
