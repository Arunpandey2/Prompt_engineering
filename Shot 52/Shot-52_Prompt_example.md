# Shot-52_Prompt

Based on the scene and shot details, here's the optimized VEO3 prompt following the guideline structure, with key elements highlighted:

### **VEO3 Prompt for Shot**

```
"Aerial extreme long shot of Lake Chelan in Washington state at 800 feet altitude, cinematic drone perspective flying eastward toward Chelan City during daytime. Camera glides smoothly across sparkling blue lake surface, gradually descending to reveal charming downtown streets with local shops and tree-lined avenues. Focus on E Woodin Avenue between N Columbia St and N Emerson St, showcasing Pacific Northwest architecture with mountain backdrop. Photorealistic 8K resolution, natural sunlight illumination, shallow depth of field when approaching street level. Shot duration: 5.2 seconds with continuous tracking movement."

```

### **Breakdown by Guideline Elements**

| **Element** | **Implementation** |
| --- | --- |
| **Subject** | Lake Chelan waters → Chelan City downtown transition |
| **Action/Verb** | "Glides smoothly eastward... gradually descending" (matches Path A 70% trajectory) |
| **Context/Setting** | "800ft altitude, 2km west of Chelan... E Woodin Ave between N Columbia/Emerson St" |
| **Style** | "Photorealistic 8K... natural sunlight" (daytime, clear weather implied) |
| **Camera Specs** | "Aerial extreme long shot... cinematic drone perspective... continuous tracking movement" |
| **Motion** | "Smooth descent from bird's-eye view to street-level medium-high angle" |

### **Negative Prompts (Critical Exclusions)**

```
"no visible people, no text/overlays, no vehicles, no unrealistic colors, no rain/fog (clear day), no close-up buildings"

```

### **Technical Alignment Notes**

1. **Duration Control**: Explicitly specified `5.2 seconds` to match audio duration
2. **Aspect Ratio**: Implicitly targets 9:16 vertical format (Aspect_9_16)
3. **Transition Prep**: Clean aerial shot allows slide overlays in post-production
4. **Character Handling**: Omitted characters (Bryan/Victor/Kevin) since shot ends before street-level detail
5. **Regional Accuracy**: Emphasized "Pacific Northwest architecture" and "Washington state" context