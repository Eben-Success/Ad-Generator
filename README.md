# CreativeAd Generator

An advanced Streamlit application that leverages Bria AI's image generation and manipulation APIs to create professional product advertisements.

## Overview

CreativeAd Generator is a comprehensive tool designed for marketers and designers to create high-quality product advertisements efficiently and professionally.

## Core Capabilities

- Generate high-definition product images from text descriptions
- Remove image backgrounds with custom color replacement
- Apply realistic shadow effects
- Create contextual lifestyle shots using text prompts or reference images
- Enhance prompts using AI technology
- Add customizable call-to-action text overlays
- User-friendly interface controls
- Simple image export functionality

## Installation

1. Clone the repository:
```bash
git clone $repo name$
cd creativead-generator
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
Create a `.env` file in the root directory with:
```bash
BRIA_API_KEY=your_api_key_here
```

4. Launch the application:
```bash
streamlit run app.py
```

## User Guide

### Basic Operations
1. Input product description or upload source image
2. Select generation parameters in sidebar
3. Configure advanced settings
4. Generate advertisement
5. Download results

### Available Settings

**Basic Options**
- AI prompt enhancement
- Background removal
- Shadow effects
- Lifestyle shot generation

**Advanced Configuration**
- Background color selection
- Shadow intensity adjustment
- Call-to-action text customization
- Lifestyle context controls