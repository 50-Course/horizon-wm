# Horizon

Dead-simple, fast, tiling window manager with dev productivity at heart :heart:

> Update: This exploratory project is currently on-hold due to the holidays
>

Building a tiling window manager from scratch is a challenging but rewarding project, and I can't wait to get started on this project. 

Here are a few things about Horizon:

1. Utlizes the X Window System:

Although an exploratory project, Horizon is intended to be built on the X-Windowing system protocol. Unsurprisely, we have the big fishes like I3 Window Manager and Sway, which are great tiling window managers for linux distros. 


Core concepts:

+ windows,
+ events,
+ and protocols is crucial.
+ Resources like the X11 protocol manual and tutorials on Xlib or XCB (libraries for interacting with X11) should be invaluable.

2. Features Roadmap

* Window Management: Simple window management functionality that automatically creates, but allows you to resize windows
* Layout Algorithms: For layout management, I am looking to explore the Fibonacci tiling layout
* Event Handling: Horizon is all about productivity. "Mouse-free development for true linux chads", Capture the heart wth keybinds and the wires the brains mappings to stay in the flow. This section should handle user input like keyboard shortcuts to trigger actions like window resizing, switching, and workspace management.
* Drawing and UI: Not main focus, but basic Terminal UI drawing skills should pass here 👀

3. Tools:

- Programming Language: As of now, the low-level language is undecided. I am looking at Rust for system-level interop, access and performance, but libraries exist for other Python and Python as the frontend.
- Libraries: I consider using existing libraries like Xlib, XCB, or Wayland (a newer alternative to X11) to simplify X interaction.
- Existing WM Codebases: I am silently exploring  existing tiling window managers like i3, and sway. Studying their code structure and implementation could provide valuable insights on how things happens down there, 🤔.
    
### Success Criteria

- The project is marked success, should i achieve basic functionality like creating and managing windows
- Focus is on core functionality: Prioritize essential features like window management, layout algorithms, and event handling -- no adding bells and whistles shit.
- Security: At this point, why memory leaks would be looked out for, this is not a priority.. Let's get something working
