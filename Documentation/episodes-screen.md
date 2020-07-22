# Creating an Episodes Screen

## Part 1

<video title="Roku SceneGraph Developers: Creating an Episodes Screen (part 1)" poster="https://image.roku.com/ZHZscHItMTc2/rsg-unit9-episodesScreen.png">
    <source src="https://image.roku.com/ZHZscHItMTc2/rsg-unit9-episodesScreen-part1.mp4">
</video>

## Part 2

<video title="Roku SceneGraph Developers: Creating an Episodes Screen (part 2)" poster="https://image.roku.com/ZHZscHItMTc2/rsg-unit9-episodesScreen.png">
    <source src="https://image.roku.com/ZHZscHItMTc2/rsg-unit9-episodesScreen-part2.mp4">
</video>


## About this lesson

This lesson explains how to build an Episodes Screen that organizes television series into seasons and episodes. The left side of the screen displays the seasons; the right side of the screen lists the episodes in the selected season. Each episode typically includes a thumbnail, title, description, and release date. When an episode is selected, its [Details Screen](/videos/courses/rsg/details-screen.md) opens and the content can then be launched into playback. This enables viewers to quickly browse through different episodes in a series to find the one they want to watch.  

This lesson shows how to use new components such as the [MarkupList](/docs/references/scenegraph/list-and-grid-nodes/markuplist.md) and further layer components to create more complex UIs. It shows how to parse the [content feed](/videos/courses/rsg/content-feed.md) to populate an episode screen with sequentially numbered seasons and the episodes that belong in those seasons. In addition, it explains how to create buttons for the different seasons in a series, and how to set the focus on an episode when a season is selected and switch the focus between the [grid](/videos/courses/rsg/grid-screen.md), episode, and [video](/videos/courses/rsg/video-player.md) screens.

## Resources

| Item                                                         | Description                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Episodes Screen sample channel](https://github.com/rokudev/scenegraph-master-sample/tree/master/EpisodesScreen) | Download and review the code used in this lesson to create an episodes screen. |
| [Sideloading  Roku channels](/docs/developer-program/getting-started/developer-setup.md#step-2-accessing-the-development-application-installer) | Sideload and test the Episodes Screen channel created in this lesson. |

## Related

[MarkupList node](/docs/references/scenegraph/list-and-grid-nodes/markuplist.md)

[LayoutGroup node](/docs/references/scenegraph/layout-group-nodes/layoutgroup.md)

[Group node](/docs/references/scenegraph/layout-group-nodes/group.md)

[Rectangle node](/docs/references/scenegraph/renderable-nodes/rectangle.md)

[Label node](/docs/references/scenegraph/renderable-nodes/label.md)

[Poster node](/docs/references/scenegraph/renderable-nodes/poster.md)

[Content node](/docs/references/scenegraph/control-nodes/contentnode.md)  

[Content meta data](docs/developer-program/getting-started/architecture/content-metadata.md)

[Handing application events](docs/developer-program/core-concepts/handling-application-events.md)

[Event loops](docs/developer-program/core-concepts/event-loops.md)

[OnKeyEvent()](/docs/references/scenegraph/component-functions/onkeyevent.md)

[ifSGNodeChildren interface](/docs/references/brightscript/interfaces/ifsgnodechildren.md)