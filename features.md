## Wardrobe pages

### Add wardrobe items by number

#### Basic usage

Add a text area to each of the different major wardrobe sections so that you can type in the numbers as you see them in the "wardrobe" screen of your game, rather than select them by mouse. Once you're done typing, you can use the "Add to Wardrobe" and "Remove from Wardrobe" buttons.

You can enter individual numbers, separated by commas (1,2,3) or you can enter number ranges using dashes (1-3) if you have a very complete collection. For example, if you have every hair, you can just type in 1-10000, and the script will figure out what needs to be added to your wardrobe. If you have all except 1 hair, you can type in 1-10000, add to your wardrobe, and then remove the one item you do not have.

#### Advanced usage

If you switch to "owned" or "not owned", the script adds a small gap every 12 items, which matches with how many items show up on each page of your wardrobe in the game.

* If your wardrobe is small, using "owned" will allow you to compare what you see to the pages of "gained" in the game.
* If your wardrobe is already mostly complete in Nikki's Info, and you have a large collection, using "not owned" will allow you to compare what you see to the pages of "not gained" in the game.

As you type into the text field, it will assume that you're planning on adding entries to your wardrobe, and it will update what's visible and re-paginate (so for "owned" it will show things, while for "not owned" it will hide things), so you can continue matching up what's on your game screen with what's on Nikki's Info.

### Add wardrobe items by suit

If you participate in an event and acquire several complete suits, the steps for adding the suits are as follows:

1. Navigate to the suits page
2. Find the region for the suit you want to add, and select it
3. Find the suit you want to add, and select it
4. Click on the selection icon at the bottom right of the page to enable select mode
5. Click on each of the individual pieces
6. Click on the save icon at the bottom right of the page
7. Repeat steps 1-6 for every suit

To simplify this process, the script adds a filter box where you can type in the name of different suits without having to find the region first, and a selection icon at the bottom right of the suits page so you don't have to navigate away to each individual suit (you can select them all at once from the index page and save from there).

If you click through to the suit page, you also will see an "Add to Wardrobe" and a "Remove from Wardrobe" button that will either add or remove all of the suit items for your wardrobe, in case you want to experiment with what suggestions would look like *if* you decide to get a new suit, and then easily remove the suit from your wardrobe when you're done checking suggestions.

### Store completion

Add a "Store Completion" button to the top of the suit list page. This checks against the store/drops metadata (derived by crawling the MyNI website) in order to check all suits to see if there are any pieces that can be bought from the store. Each suit will be annotated with the estimated cost in gold and jewels for the items that can be bought from the store, and each item will be marked with a black border.

This same feature also appears on each individual suit page as an "Approximate Value" button, which uses the crafting tree (derived by crawling the MyNI website) in order to approximate the value for each piece of the suit, based on the approximate cost to buy any ingredient from the store.

* The crafting tree was last updated October 13, 2019.
* The store/drops metadata was last updated October 13, 2019.

### Safe decompose

Add a "Check for Safe Decompose" button to the top of each wardrobe page. This checks against the crafting tree (derived by crawling the MyNI website) in order to add markers indicating how much of the crafting tree for that item has been completed. From there, it's possible to know whether it's safe to decompose an item in your wardrobe.

* The crafting tree was last updated October 13, 2019.

## Wardrobe item pages

### Add drop location tags

Add all of the different drop types (such as "clothes store") as a tag.

### Add "Identify all" button to "Crafted from" and "Used to craft" wardrobe item sections

Sometimes you wonder, "Do I still need to collect more of this item?" In order to find that out, you need to follow the crafting tree for every item that this item can make, and then every item that those items can make. In other words, you need to identify all of the transitive dependencies!

This script adds a button to each item's page which you can use to have the script follow the crafting tree and present you with all of the items, marking whether you've added them to your wardrobe. The items are also compatible with the select and save button that's present on item pages, so if you know you already have already crafted that dependency, you can also add them directly to your wardrobe. The script also adds the slightly less useful feature which follows the crafting tree in reverse to discover every item that contributed into making the item.

## Stage list pages

### Show base score for stylist arena stages

In the list of arena stages, show the base score for the current outfit recommendation, and add a "New" tag to the stage if the MyNI guide recommends that you update your outfit in order to achieve that new base score.

### Show commission stage base scores by progress

When doing Commissions, the game offers a "Switch Act" option, which will present you with a list of acts and the progress your stylist association has made for each act. This script adds a small text field to each stage, where you can enter your stylist association's progress, and it will show you which stage they are on and your current base score for that stage.

## Guide pages

### Add "game order" as a sort option for MyNI guide

When using "category order" for the MyNI guide in order to setup a new outfit for a stage, it's easy to lose track of what you have or haven't done, because the accessories aren't grouped in the same way as the game. Often, you might put together some headwear pieces, skip around, and then come back to finish additional headwear pieces. This script adds an extra option, "game order", to present everything in the same order as the game.

### Add "check stage-matching attributes" button to MyNI guide

When you're newer to the game, your wardrobe is small, so it's hard to know whether you can do better on a stage. An easy way to get around that is to check the lower scoring items on the list (most likely accessories), and then check to see if they have high grades for the main stage attributes. Checking things one at a time is pretty tedious, so this checks them all at once.

### Auto-load bookmarked custom stages

Auto-submit bookmarked custom stages to save you a click.

## Miscellaneous pages

### Filter item drops by name

On the "Drops and Stores" page, add a filter box where you can type in the partial name of a drop item, and it will show just the items that match that part of the name.

### Use drop location as a tag

On the "Tags" page, add all of the different drop types (such as "clothes store") as a tag, in case you want to check if there's an item that is better than any of your existing items due to matching all of the tags for an area.

Since there are people who prefer items that you acquire via gold rather than via diamonds, or they might prefer to just use stamina to acquire the item, the script also adds any information that's listed on the drops page to the tag search results.