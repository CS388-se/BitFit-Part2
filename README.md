# Android Project 6 - *BitFit-Part2*

Submitted by: **Stephen Ebrahim**

**BitFit-Part2** is a health metrics app that allows users to track the how much calories you consume as well as display some statistics regarding those calroies.

Time spent: **6** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] **Use at least 2 Fragments**
- [X] **Create a new dashboard fragment where users can see a summary of their entered data**
- [X] **Use one of the Navigation UI Views (BottomNavigation, Drawer Layout, Top Bar) to move between the fragments**

The following **optional** features are implemented:

- [ ] **Add a more advanced UI (e.g: Graphing) for tracking trends in metrics**
- [ ] **Implement daily notifications to prompt users to fill in their data**

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![Kapture 2023-03-03 at 15 20 43](https://user-images.githubusercontent.com/66531257/222821099-6177c37d-12f3-4d71-89b7-ce6aa1a14365.gif)

GIF created with [Kap](https://getkap.co/) for macOS.

### More screenshots to prove requirements:
- Here I just wanted to show the 2 Fragments: `DashboardFragment` and `FoodListFragment`

![Screenshot 2023-03-03 at 3 22 57 PM](https://user-images.githubusercontent.com/66531257/222821407-85184289-c055-4e1d-b52b-6dd98c828edd.png)

## Notes

The biggest challenge was getting the list of data on the dashboard fragment; I later realized that I just need to query the database and used the `getAll` method to retreive all the items.

## License

    Copyright [2023] [Stephen Ebrahim]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
