# exiftool
# Image Metadata Investigation Using ExifTool

## 1. Introduction

### What is ExifTool?

ExifTool is a powerful, open-source, command-line tool used to read, write, and edit metadata embedded in images and many other file formats.

It is commonly used in Digital Forensics, OSINT (Open-Source Intelligence), and Image Investigation to extract useful information from digital files.

### Who Developed ExifTool?

ExifTool was developed by **Phil Harvey**. It is available as a Perl library and a command-line application.

**Official Resources:**
- [ExifTool Official Website](https://exiftool.org/)
- [ExifTool GitHub Repository](https://github.com/exiftool/exiftool)

---

## 2. Features of ExifTool

ExifTool provides several features that make it useful for digital investigations:

1. Extract metadata from images and digital files.
2. Read EXIF, GPS, IPTC, and XMP metadata.
3. Identify the camera manufacturer and device model.
4. Extract the recorded date and time of an image.
5. Extract GPS coordinates, including latitude and longitude.
6. Retrieve image dimensions, resolution, and file format.
7. Identify camera settings such as ISO, Aperture, and Shutter Speed.
8. Support a wide range of image, video, and other file formats.
9. Export metadata into different formats, including JSON, HTML, and XML.
10. Read, write, edit, and remove metadata.

---

## 3. What Information Can We Extract?

ExifTool can extract different types of information depending on the metadata available in the image.

| Metadata Category | Examples |
|---|---|
| Device Information | Camera Make, Camera Model |
| Date & Time | Date Taken, Create Date, Modify Date |
| GPS Information | Latitude, Longitude, Altitude |
| Image Information | Width, Height, Format |
| Camera Settings | ISO, Aperture, Shutter Speed |
| Software Information | Editing Software |
| Author Information | Artist, Copyright |
| Image Details | Orientation, Resolution |

### Why Is This Information Important?

Metadata plays an important role in Digital Forensics and OSINT investigations because it can reveal hidden information about a digital image that is not visible to the human eye.

By analyzing image metadata, investigators can:

- **Identify the Location:** Extract GPS coordinates to determine where a photo may have been taken.
- **Determine the Date and Time:** Identify the recorded date and time associated with the image.
- **Identify the Device:** Discover the camera manufacturer, device model, and other technical details.
- **Analyze Image History:** Identify information about editing software or applications used to process the image.
- **Build an Investigation Timeline:** Use available timestamps to help organize events chronologically.
- **Support Digital Investigations:** Collect additional technical information that may help verify or investigate digital evidence.

**Important Note:** Metadata should not be considered definitive proof on its own. It can be missing, modified, or manipulated. Therefore, investigators should always verify extracted information using additional sources and evidence.

---

### Step 1 – Running ExifTool Using CMD

First, open **Command Prompt (CMD)** on Windows.

Navigate to the folder where ExifTool is installed using the `cd` command, followed by the folder path.


Once you are inside the ExifTool directory, execute the tool by typing `exiftool` followed by the path of the image you want to investigate.



ExifTool will analyze the selected image and display all available metadata in the Command Prompt window.
<img width="942" height="486" alt="exiftool run" src="https://github.com/user-attachments/assets/8c08a6d6-911c-4d93-a560-cb390a9dc00d" />
