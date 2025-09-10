# GemSeek 

GemSeek is a gemstone identification application designed to simplify the process of identifying gemstones for both casual users and geological researchers. It leverages a unique system of "Knowledge Sources" using Blackboard architecture to provide accurate and reliable identification results.

---

## Features 

* **Gemstone Identification:** Users can identify gemstones by uploading an image and selecting descriptive tags.
* **"Find Gemstone" Search:** A single, streamlined search feature that combines user-provided tags and an image for precise identification.
* **knowledge source System:** The app utilizes three independent knowledge sources to analyze user input:
    * **Gemstone Database:** Filters results based on predefined tags.
    * **ChatGPT API:** Analyzes the provided image for identification.
    * **Gemini API:** Cross-references the image to find similar results.
* **Conflict Resolution Forum:** An internal system that aggregates responses from the knowledge sources and resolves any conflicts to present a single, final identification.
* **User Upvoting System:** Users can rate the accuracy of past identifications, which helps refine and improve the reliability of future search results.
* **Educational Resources:** The app provides detailed information about identified gemstones, including their **natural environments, physical properties, and chemical characteristics**, encouraging interest in geology.

---

## How It Works

When a user initiates a search, the image and tags are submitted to the three knowledge source systems. Each knowledge source provides a response based on its domain. These responses are then sent to a central forum where any conflicting results are resolved. The forum's decision is the final identification presented to the user. This multi-faceted approach ensures a high degree of accuracy.

---

## Project Goals

The primary objective of GemSeek is to **reduce the time and effort** required for gemstone identification. By simplifying the process through an intuitive and structured approach, the app makes it accessible to everyone. A secondary goal is to **increase user engagement**, as a growing user base strengthens the upvoting system, which in turn improves the reliability of the application's results. Additionally, GemSeek aims to **encourage interest in geology** by serving as an educational and accessible tool for both enthusiasts and professionals.