# Minimal Recommendation Engine
We build a recommendation engine with a data set which contains 1 million ratings collected from 6000 users on 4000 movies from MovieLens.

## Roadmap

What exactly are we going to do? Here's a high-level overview:

- quick introduction to the recommendation problem (theory)
- learn about Pandas Series and DataFrames (practice) 
- known solutions & challenges to the recommendation problem (theory) 
- load data, setup evaluation functions, test dummy solution (practice) 
- minimal reco engine v1.0 (practice) 
- more formulas! (theory) 
- pandas aggregation & minimal reco engine v1.1 (practice) 
- challenge (practice) 

## The Recommendation Problem

Recommenders have been around since at least 1992. Today we see different flavours of recommenders, deployed across different verticals: 

- Amazon
- Netflix
- Facebook
- Last.fm.

What exactly do they do?

### Definitions from the literature

- *In a typical recommender system people provide recommendations as inputs, which
the system then aggregates and directs to appropriate recipients.* -- Resnick
and Varian, 1997

- *Collaborative filtering simply means that people collaborate to help one
another perform filtering by recording their reactions to documents they read.*
-- Goldberg et al, 1992

- *In its most common formulation, the recommendation problem is reduced to the
problem of estimating ratings for the items that have not been seen by a
user. Intuitively, this estimation is usually based on the ratings given by this
user to other items and on some other information [...] Once we can estimate
ratings for the yet unrated items, we can recommend to the user the item(s) with
the highest estimated rating(s).* -- Adomavicius and Tuzhilin, 2005

- *Driven by computer algorithms, recommenders help consumers
by selecting products they will probably like and might buy
based on their browsing, searches, purchases, and preferences.* -- Konstan and Riedl, 2012
