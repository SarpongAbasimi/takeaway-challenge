# Takeaway Challenge.

# Knowleged Needed To solve This Challenge.
- Encapsulation.
- RSpec doubles.
- Abstraction.
- Dependency Injection.
- Working with API (Twilio API).

How To Use This Application.
-------
- Fork this repo.
- clone it on your local computer `` git clone.``
- cd into the directory.
- Run bundle intall to install all the dependencies or the application.
- In terminal ``type irb. ``
- ``require './lib/take_away ``
- Create a new menu object ``menu = Menu.new() ``|| ``Note: menu can takes one optional argument. ``
- Create a new take way object ``take_away = TakeAway.new(menu).``

##### In terminal type `` rspec`` to run test.

# Takeaway-Challenge In IRB.
> How the application works currently.
<img width="187" alt="Screen Shot 2019-04-14 at 23 30 15" src="https://user-images.githubusercontent.com/37377831/56100318-1ef48400-5f0f-11e9-86f5-2de90018e2b6.png">
<img width="159" alt="Screen Shot 2019-04-14 at 23 31 15" src="https://user-images.githubusercontent.com/37377831/56100287-bb6a5680-5f0e-11e9-9875-04299eb15bd9.png">
<img width="753" alt="Screen Shot 2019-04-14 at 23 31 38" src="https://user-images.githubusercontent.com/37377831/56100331-3fbcd980-5f0f-11e9-8e0d-b90e2e04be30.png">
<img width="1074" alt="Screen Shot 2019-04-14 at 23 32 40" src="https://user-images.githubusercontent.com/37377831/56100397-1f414f00-5f10-11e9-8d87-6674b369a93a.png">
<img width="583" alt="Screen Shot 2019-04-14 at 23 34 23" src="https://user-images.githubusercontent.com/37377831/56100405-3d0eb400-5f10-11e9-9a7a-7d8d49aa29ec.png">
<img width="297" alt="Screen Shot 2019-04-15 at 09 31 12" src="https://user-images.githubusercontent.com/37377831/56118102-82a79d00-5f61-11e9-9936-a31b6d95de25.png">
<img width="311" alt="Screen Shot 2019-04-15 at 09 32 09" src="https://user-images.githubusercontent.com/37377831/56118209-acf95a80-5f61-11e9-880a-aa6f6a9824f4.png">

# Objects & Subject from User Story.

| object   | subjects |
|----------|----------|
|  Menu    |list_dish |
|TakeAway  |show_menu / select_dish|
|Order     |user_choice / total_order|

# challenges.
- I was only able to complete the first 3 user stories.
- Difficulty in modelling the objects.
# Improvement.
- Refactoring the codebase.
- Improving object structure.
- Improving test.
# To Do.
- Integrate Twillo API into the application.
- Create a friendly user interface.

# Test Coverage.
> 100%
