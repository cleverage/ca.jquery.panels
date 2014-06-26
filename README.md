jQuery Panels Plug-in
=====================

This plugin provides a simple and elegant abstraction level to your sliders / carousels / tabs / _whatevernameyouwant_. We simply call them **panels**. We observe that whatever their names are, those components have always the same logic: you can switch between their children. Maybe with a pagination, maybe with prev / next; sometimes with 3 items visible at once, sometimes only one. But the logic remains: you switch between panels.

So the plugin itself simply offers the API to deal with your panels, and is flexible and customizable throught its options. It does **not** do transitions by itself. You'll need to load a subengine that brings this behaviours. This is the killer-feature of this plugin: instead of loading a huge plugin with more options and capabilities, you only take the display engine(s) you need, and it's over.
