# R-and-Azure-OCR
Error in Azure OCR using R
i used the below code to scan text from image but it does not work for me.

    library(AzureVision)
    library(httr)
    library(jsonlite)
    Endpoint ->
    APIKey ->
    img_link -> "https://images.app.goo.gl/BHLmtfLJxbwdRo99A"
    read_text(endpoint = Endpoint, image = img_link, detect_orientation = TRUE, language = "en" )
i got the following error
Error in UseMethod("call_cognitive_endpoint") : no applicable method for 'call_cognitive_endpoint' applied to an object of class "character"
anyone can help?
