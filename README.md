# Lab8-Starter
Matthew Gunawan
Pages: https://matthewgunawann.github.io/Lab8_Starter/

Answer (How are graceful degradation and service workers related?):
Graceful degradation and service workers go hand-in-hand, as the service worker enables a web app to gracefully degrade in the absence of network. Graceful degradation is a technique wherein the application delivers a full-fledged experience initially, and it continues to function at a lower level should an issue arise. Service workers help with this by intercepting requests on the network and providing locally stored copies of resources such as HTML, CSS, JavaScript, images and JSON data. This gives the app the ability to present content even if the user doesn't have an internet connection or a slow one. Our recipe cards were still there offline in this lab, as the service worker had cached all the resources we needed on the initial load.
