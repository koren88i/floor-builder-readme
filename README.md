# Floor Builder

Floor Builder turns a floor-plan image into editable rooms and a multi-floor building view. This public repository shows the workflow; the application source and live project data remain private.

## Workflow

1. **Import and review.** Upload a floor-plan image and compare it with suggested walls and rooms. Detection favors longer lines and filters isolated small boxes containing text-like marks to reduce false walls from labels. Boxes near other geometry stay available for review; draw missing short walls manually. Saved layouts are preserved.

   ![Simple demo plan with suggested rooms overlaid on the source image](images/photo-overlay.jpg)

2. **Assign rooms.** Select a room, record its seats and area, and assign teams with headcounts. The room shows its total and free seats.

   ![Room details with a synthetic team assignment](images/room-details.jpg)

3. **Explore floors.** Add another floor from a plan or copy a layout with empty assignments. A schematic 3D view shows the floors together.

   ![Schematic 3D view of two demo floors](images/building-3d.jpg)

4. **Find and review.** Filter the rooms report by Anaf or Mador, open a room from the results, and use saved revisions to recover earlier work.

   ![Rooms report filtered to a synthetic Mador](images/rooms-report.jpg)

All screenshots use synthetic assignments and a [public-domain demo plan by Ashlynn Schindler](https://commons.wikimedia.org/wiki/File:Floor_plan_1.jpg). Suggested walls and rooms are provisional.
