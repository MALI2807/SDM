Key Features :

    Unit Selection Dropdown

        Added a clean selector between feet (ft) and meters (m)

        Positioned next to the upload button for easy access

    Automatic Unit Conversion

        All calculations done internally in meters

        Converts to feet for display when selected

        TVD calculations respect the selected units

    Dynamic Axis Labeling

        X-axis now shows "MD (ft)" or "MD (m)"

        TVD chart Y-axis matches the selected units

    Improved Number Formatting

        Added a niceIncrement() function for better axis ticks

        Ensures clean, rounded numbers on scales

    Consistent Unit Handling

        All charts now properly respect the unit selection

        Unit conversion happens in one place (getDisplayMD function)

    Professional Layout

        Clean control panel layout

        Proper spacing between controls

        Clear labeling
