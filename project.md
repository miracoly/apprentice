# Microgreen Office-Suite

## MVP - Minimum viable product
- Grow-Cycle Tracker

## User Stories
- user wants to harvest a specific amount of microgreens on a specific date
	- user creates a new grow cycle
		- he specifies the date, when to harvest
		- he chooses the grow method from a predefined list, which determines the steps to accomplish the goal
		- he specifies the varieties he wants to harvest
		- he specifies the amount he wants to harvest
	- the software lists all steps in an ordered manner
		- the user sees when to plant the seeds, when to remove pressure, when to
			water etc.
		- the user can check each item when he finished the task
	- on harvest day he can track the harvest amount
- user sees all grow cycles and can browse through past ones

## Use Cases
- create new grow cycle
- edit existing grow cycle

## Data

### Tracked Data
- cycle-number
- seed vendor
- lot number
- weight seeds
- weight seeds per tray
- soaked at
- hours soaked
- planted at
- weight till
- blackout till
- under light
- hours light per day
- harvest weight per variety

### Calculated Data
- average harvest weight 
- seed/harvest ratio
- tray quantity


## Constrains
- predefined microgreens
	- varieties
		- peashoots
		- sunflower
		- reddish
	- predefined seed/harvest ratio
- predefined grow methods
	- standard tray method, same for all varieties

## Technologie
- Backend
	- Spring Boot
	- Postges Db ???
- Frontend
	- ReactJs
		- Jest with React Testing Library
	- Typescript
	- Redux for State Management
	- React-Router

## Next Steps
- user can add more microgreens
- user can define own grow methods
- software caluclates seed/harvest ratio from last grow cycles for each grow methods
- user can compare grow methods
- Revenue Logbook
	- for Market
	- for Restaurant
