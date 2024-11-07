# Ark - Left

All aboard the Ark! I hope this helps with migration.

This [Zen Browser](https://zen-browser.app/) theme aims to capture Arc Browser's essence with pure css. Primarily, this is achieved by removing the top toolbar, relocating the most used buttons to the top of the sidebar along with the URL bar, which also receives suitable styling.

There are two opt-in customisations included within user preferences:
- Maintain Default Sidebar Width (keep at 215px)
- Hide HTTP Warning Icon (for sites without SSL)

A few things aren't feasible without javascript:
- Automatically opening the full URL bar when a new tab is created
- Having two different open URL bar interfaces: one on the left when clicking within, a launchbar in the middle when hitting CMD + L (or CMD + T as above)
- Showing the full URL launchbar in the center when active, while simultaneously keeping the current URL bar visible on the left

For the above reasons, the most pragmatic approach seemed to be keeping the URL bar on the left for both closed or opened states. Its open state more closely resembles Arc's full Launchar than the smaller editing interface. Hopefully one day we'll get a native centred launchbar in Zen!

Note: This is being released during Zen Browser's Alpha stage and thus has a high probability of breaking as the project matures.
