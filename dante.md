# Dante

Dante is required knowledge to get certified in the Machine Room, Davis Studio, and Control Room. Comprehensive information about Dante is covered in our Dante [training module](https://sites.google.com/umich.edu/pat/training).

## Dante Controller

## Dante Virtual Soundcard

## RedNet

## The Default Preset

When you log in to any computer connected to the Dante network, a "Dante Presets" folder will be placed on your Desktop. For nearly all use cases, the Default Preset should suffice. We prefer that you do temporary patches through the patch bay rather than with Dante, unless you need to create something that is repeatable.

Below are all the routings for the Default Preset

### Davis: Mac Pro (via RedNet PCIe)

<!-- tabs:start -->

#### **Inputs**

- **1-10**: From RedNet 2 #3 *INPUT* **7-16**

<details>
<summary>View Table</summary>

| Source Device | Source Channel | RedNet PCIe Channel |
| --- | --- | --- |
| RedNet 2 #3 | 1 | 7 |
| RedNet 2 #3 | 2 | 8 |
| RedNet 2 #3 | 3 | 9 |
| RedNet 2 #3 | 4 | 10 |
| RedNet 2 #3 | 5 | 11 |
| RedNet 2 #3 | 6 | 12 |
| RedNet 2 #3 | 7 | 13 |
| RedNet 2 #3 | 8 | 14 |
| RedNet 2 #3 | 9 | 15 |
| RedNet 2 #3 | 10 | 16 |

</details>

#### **Outputs**

- **1-2**: Stereo out to Roland M-5000 **1-2**
- **3-25**: To *Davis Ambisonic System*

<details>
<summary>View Table</summary>

| RedNet PCIe Channel | Destination Device | Destination Channel |
| --- | --- | --- |
| 1 | Roland M-5000 | 1 |
| 2 | Roland M-5000 | 2 |
| --- | --- | --- |
| 3 | Ambisonic System (via RedNet 2 #2) | 1 |
| 4 | Ambisonic System (via RedNet 2 #2) | 2 |
| 5 | Ambisonic System (via RedNet 2 #2) | 3 |
| 6 | Ambisonic System (via RedNet 2 #2) | 4 |
| 7 | Ambisonic System (via RedNet 2 #2) | 5 |
| 8 | Ambisonic System (via RedNet 2 #2) | 6 |
| 9 | Ambisonic System (via RedNet 2 #2) | 7 |
| 10 | Ambisonic System (via RedNet 2 #2) | 8 |
| 11 | Ambisonic System (via RedNet 2 #2) | 9 |
| 12 | Ambisonic System (via RedNet 2 #2) | 10 |
| 13 | Ambisonic System (via RedNet 2 #2) | 11 |
| 14 | Ambisonic System (via RedNet 2 #2) | 12 |
| 15 | Ambisonic System (via RedNet 2 #2) | 13 |
| 16 | Ambisonic System (via RedNet 2 #2) | 14 |
| 17 | Ambisonic System (via RedNet 2 #2) | 15 |
| 18 | Ambisonic System (via RedNet 2 #2) | 16 |
| 19 | Ambisonic System (via RedNet 2 #3) | 1 |
| 20 | Ambisonic System (via RedNet 2 #3) | 2 |
| 21 | Ambisonic System (via RedNet 2 #3) | 3 |
| 22 | Ambisonic System (via RedNet 2 #3) | 4 |
| 23 | Ambisonic System (via RedNet 2 #3) | 5 |
| 24 | Ambisonic System (via RedNet 2 #3) | 6 |
| 25 | Ambisonic System (via RedNet 2 #3) | 7 |

</details>

<!-- tabs:end -->

### Davis: Roland M-5000

<!-- tabs:start -->

#### **Inputs**

- **1-2**: Stereo in from Mac Pro
- **3-18**: From RedNet 2 #1 *INPUT* **1-16**
- **19-34**: From RedNet 2 #2 *INPUT* **1-16**
- **35-40**: From RedNet 2 #3 *INPUT* **1-6**
- **41-48**: From RedNet MP8R #1 **1-8**
- **49-56**: From RedNet MP8R #2 **1-8**
- **57-64**: From RedNet MP8R #3 **1-8**

<details>
<summary>View Table</summary>

| Source Device | Source Channel | Roland M-5000 *Dante* Channel |
| --- | --- | --- |
| Davis Mac Pro | 1 | 1 |
| Davis Mac Pro | 2 | 2 |
| --- | --- | --- |
| RedNet 2 #1 | 1 | 3 |
| RedNet 2 #1 | 2 | 4 |
| RedNet 2 #1 | 3 | 5 |
| RedNet 2 #1 | 4 | 6 |
| RedNet 2 #1 | 5 | 7 |
| RedNet 2 #1 | 6 | 8 |
| RedNet 2 #1 | 7 | 9 |
| RedNet 2 #1 | 8 | 10 |
| RedNet 2 #1 | 9 | 11 |
| RedNet 2 #1 | 10 | 12 |
| RedNet 2 #1 | 11 | 13 |
| RedNet 2 #1 | 12 | 14 |
| RedNet 2 #1 | 13 | 15 |
| RedNet 2 #1 | 14 | 16 |
| RedNet 2 #1 | 15 | 17 |
| RedNet 2 #1 | 16 | 18 |
| --- | --- | --- |
| RedNet 2 #2 | 1 | 19 |
| RedNet 2 #2 | 2 | 20 |
| RedNet 2 #2 | 3 | 21 |
| RedNet 2 #2 | 4 | 22 |
| RedNet 2 #2 | 5 | 23 |
| RedNet 2 #2 | 6 | 24 |
| RedNet 2 #2 | 7 | 25 |
| RedNet 2 #2 | 8 | 26 |
| RedNet 2 #2 | 9 | 27 |
| RedNet 2 #2 | 10 | 28 |
| RedNet 2 #2 | 11 | 29 |
| RedNet 2 #2 | 12 | 30 |
| RedNet 2 #2 | 13 | 31 |
| RedNet 2 #2 | 14 | 32 |
| RedNet 2 #2 | 15 | 33 |
| RedNet 2 #2 | 16 | 34 |
| --- | --- | --- |
| RedNet 2 #3 | 1 | 35 |
| RedNet 2 #3 | 2 | 36 |
| RedNet 2 #3 | 3 | 37 |
| RedNet 2 #3 | 4 | 38 |
| RedNet 2 #3 | 5 | 39 |
| RedNet 2 #3 | 6 | 40 |
| --- | --- | --- |
| RedNet MP8R #1 | 1 | 41 |
| RedNet MP8R #1 | 2 | 42 |
| RedNet MP8R #1 | 3 | 43 |
| RedNet MP8R #1 | 4 | 44 |
| RedNet MP8R #1 | 5 | 45 |
| RedNet MP8R #1 | 6 | 46 |
| RedNet MP8R #1 | 7 | 47 |
| RedNet MP8R #1 | 8 | 48 |
| --- | --- | --- |
| RedNet MP8R #2 | 1 | 49 |
| RedNet MP8R #2 | 2 | 50 |
| RedNet MP8R #2 | 3 | 51 |
| RedNet MP8R #2 | 4 | 52 |
| RedNet MP8R #2 | 5 | 53 |
| RedNet MP8R #2 | 6 | 54 |
| RedNet MP8R #2 | 7 | 55 |
| RedNet MP8R #2 | 8 | 56 |
| --- | --- | --- |
| RedNet MP8R #3 | 1 | 57 |
| RedNet MP8R #3 | 2 | 58 |
| RedNet MP8R #3 | 3 | 59 |
| RedNet MP8R #3 | 4 | 60 |
| RedNet MP8R #3 | 5 | 61 |
| RedNet MP8R #3 | 6 | 62 |
| RedNet MP8R #3 | 7 | 63 |
| RedNet MP8R #3 | 8 | 64 |


</details>

#### **Outputs**

- **1-16**: To *Davis surround system*
- **17-26**: To RedNet 2 #3 *OUTPUT* **7-16**

<details>
<summary>View Table</summary>

| Roland M-5000 Channel | Destination Device | Destination Channel |
| --- | --- | --- |
| 1 | Davis Surround System (via RedNet 2 #1) | 1 |
| 2 | Davis Surround System (via RedNet 2 #1) | 2 |
| 3 | Davis Surround System (via RedNet 2 #1) | 3 |
| 4 | Davis Surround System (via RedNet 2 #1) | 4 |
| 5 | Davis Surround System (via RedNet 2 #1) | 5 |
| 6 | Davis Surround System (via RedNet 2 #1) | 6 |
| 7 | Davis Surround System (via RedNet 2 #1) | 7 |
| 8 | Davis Surround System (via RedNet 2 #1) | 8 |
| 9 | Davis Surround System (via RedNet 2 #1) | 9 |
| 10 | Davis Surround System (via RedNet 2 #1) | 10 |
| 11 | Davis Surround System (via RedNet 2 #1) | 11 |
| 12 | Davis Surround System (via RedNet 2 #1) | 12 |
| 13 | Davis Surround System (via RedNet 2 #1) | 13 |
| 14 | Davis Surround System (via RedNet 2 #1) | 14 |
| 15 | Davis Surround System (via RedNet 2 #1) | 15 |
| 16 | Davis Surround System (via RedNet 2 #1) | 16 |
| --- | --- | --- |
| 17 | RedNet 2 #3 | 7 |
| 18 | RedNet 2 #3 | 8 |
| 19 | RedNet 2 #3 | 9 |
| 20 | RedNet 2 #3 | 10 |
| 21 | RedNet 2 #3 | 11 |
| 22 | RedNet 2 #3 | 12 |
| 23 | RedNet 2 #3 | 13 |
| 24 | RedNet 2 #3 | 14 |
| 25 | RedNet 2 #3 | 15 |
| 26 | RedNet 2 #3 | 16 |

</details>

<!-- tabs:end -->

## Creating "safe" presets