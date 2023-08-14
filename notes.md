## Properties

Every grid is composed pf 2 main groups:

`container (father)` and `items (children)`

# Container

- display: grid
- grid-template:
    - grid-template-columns;
        - repeat(number of times want to repeat, the value) eg. repeat(3, 1fr)
    - grid-template-rows;
    - grid-template-areas;
- gap
   - row-gap;
   - column-gap;

# Items

- grid-column;
    - grid-column-start;
    - grid-column-end;
- grid-row;
    - grid-row-start;
    - grid-row-end;

# Alignment properties

There are 9

** 6 applied to the container
`align-content`
`justify-content`
`place-content`

`align-items`
`justify-items`
`place-self`

** 3 applied to the items
`align-self`
`justify-self`
`place-self`

We can separate in 3 groups
`align`,  `justify`, `place`

Each will observe:
 - element content: `content`
 - element items: `items`
 - element itself: `self` 

# AUTO properties
 - grid-auto-flow
 - grid-auto-rows
 - grid- auto-columns