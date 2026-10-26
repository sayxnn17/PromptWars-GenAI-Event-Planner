# All models defined here, should be implemented as Pydantic objects in the project.

## 1. event:
- event_type: This has to be either birthday, wedding or community event
- event_name: This contains the name of the event
- event_date: This is the date when the event is scheduled to take place.
- budget: This is the total budget of the event, thus it must support float data-type.
- location: This is where the event is to take place.
- indoor_preference: if True, then the event is an indoor event, otherwise it is meant to be an outdoor event.
- overall_style: This is a single string that describes the overall style of the event.
- set_priority: This is a list of 3 strings that the user wants to spend the most amount of money on.
- customizations: This is a set of strings containing the instructions that the user provides from their own side.

## 2. plan:
- budget_split: This describes how the total budget of the event is distributed among the various aspects.
- backwards_oriented_timeline: This describes the flow of tasks that need to be completed before and/or after the event.
- vendor_list: This is the list of vendors providing the various servies like catering, decorations etc. that would be needed for the event.
