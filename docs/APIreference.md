# API reference

## Rendering YouTube videos

??? note "example"
    ### Short example
    ```python
    from NotebookPlaylink.youtube import render_youtube_video

    URL = "https://www.youtube.com/live/h25pePMdoPA?si=B0v6zKKtX2S92D7-"
    render_youtube_video(URL=URL, width=780, height=480)
    ```

### Arguments

| Args   | Type | Description                                                         |
| ------ | ---- | ------------------------------------------------------------------- |
| URL    | str  | input URL of a YouTube video as a string                            |
| height | int  | height of the video to display in Jupyter notebook, defaults to 480 |
| width  | int  | width of the video to display in Jupyter notebook, defaults to 780  |

### Returns

| Returns  | Type | Description                              |
| -------- | ---- | ---------------------------------------- |
| Response | str  | `"success"` or `InvalidURLException` |


## Rendering reference website

??? note "example"
    ### Short example
    ```python
    from NotebookPlaylink.site import render_site

    URL = "http://pytorch.org/"
    render_site(URL=URL, width="90%", height="500")
    ```

### Arguments

| Args   | Type | Description                                                                 |
| ------ | ---- | --------------------------------------------------------------------------- |
| URL    | str  | input URL of a website as a string                                          |
| height | str  | height of the website to display in Jupyter notebook, defaults to `"600"` |
| width  | str  | width of the website to display in Jupyter notebook, defaults to `"100%"` |

### Returns

| Returns  | Type | Description                              |
| -------- | ---- | ---------------------------------------- |
| Response | str  | `"success"` or `InvalidURLException` |
