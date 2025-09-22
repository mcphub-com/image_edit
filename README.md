# Image Editor MCP

An MCP server that provides AI-powered image editing capabilities through natural language prompts.

## Overview

This MCP server offers an image editing tool that uses AI models to modify images based on text descriptions. Users can provide an image URL and an editing prompt to receive an edited version of the image.

## Available Tools

### Image Editing (`image_edit`)

Edits an image based on a text prompt description.

**Parameters:**
- `image` (string): The URL of the image to be edited
  - Example: `"https://example.com/images/photo.jpg"`
- `prompt` (string): A text description explaining how to edit the image
  - Example: `"Change the background to a beach scene with sunset"`
  - Example: `"Make it look like winter with snow and Christmas decorations"`
  - Example: `"Remove the person on the left and fill in the background appropriately"`

**Functionality:**
This tool takes an image URL and an editing prompt, processes the image using AI models according to the instructions, and returns the edited image.

## Usage

Invoke the `image_edit` tool through your MCP client with the required parameters:

```
/image_edit https://example.com/input.jpg "Add a dramatic sky with clouds and sunlight"
```
