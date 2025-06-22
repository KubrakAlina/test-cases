# Please use Node v20.11.1 (or higher)

Make a fork of this repository.
You can edit any file you want.

### With Autodesk account
### Task 1 (need to provide access to model URN)
Goal: Set up a simple web app with Autodesk Viewer to load and display a model using a provided URN.
###### Main points:
-	Load a model in Autodesk Viewer using a given URN (mock URN or environment variable).
-	Display a fallback message if the model fails to load.
-	Load the viewer in a wrapper component (e.g., <ModelViewer />) that accepts the URN as a prop.

### Task 2 (need the first to be done)
Goal: Display the model hierarchy (e.g., categories, elements) in a sidebar, similar to Autodesk Model Browser.
###### Main points:
-	Use viewer.getObjectTree() to fetch hierarchy.
-	Render a collapsible tree structure (nested list).
-	Highlight the selected node when clicked.
-	Zoom to the object in the viewer when clicked.

###### Additional:
-	Sync selection from the viewer back to the tree.

### Without Autodesk account
### Task 1
Goal: Create a list of items (use /src/data/nfsTestData.json)
###### Main points:
- Create reusable components for Item and List.
- By clicking on Item shows full data in Modal or dropdown.
- Inside the Modal or dropdown shows the list of elements from the 'geometries' property.

###### Additional:
- Make the List virtualized.
- Add simple filtering, searching, etc.

### Task 2
Goal: Create a function to manipulate tags in the NF items (use /src/data/nfsTestData.json and /src/data/testTags.json)
###### Main points:
- Create a simple list or use the result of task 1 above.
- Manipulate and save tags for items in the list (use tags from the file)

###### Additional:
- Grouping, sorting, filtering by tags.
