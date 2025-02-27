{\rtf1\ansi\ansicpg1252\cocoartf2821
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 import java.awt.Color;\
import java.awt.image.BufferedImage;\
import java.io.File;\
import java.net.URL;\
import java.util.Arrays;\
import java.util.Random;\
import javax.imageio.ImageIO;\
public class ImageProcessing \{\
	public static void main(String[] args) \{\
    // The provided images are apple.jpg, flower.jpg, and kitten.jpg\
		int[][] imageData = imgToTwoD("./apple.jpg");\
    viewImageData(imageData);\
    // Or load your own image using a URL!\
		//int[][] imageData = imgToTwoD("https://content.codecademy.com/projects/project_thumbnails/phaser/bug-dodger.png");\
		\
		int[][] trimmed = trimBorders(imageData, 60);\
\
		twoDToImage(trimmed, "./trimmed_apple.jpg");\
		\
\
		int[][] negative = negativeColor(imageData);\
\
		twoDToImage(negative, "./negative_apple.jpg");\
		\
\
		int[][] stretchedHImg = stretchHorizontally(imageData);\
\
		twoDToImage(stretchedHImg, "./stretched_apple.jpg");\
		\
\
		int[][] shrankVImg = shrinkVertically(imageData);\
\
		twoDToImage(shrankVImg, "./shrank_apple.jpg");\
		\
\
		int[][] invertedImg = invertImage(imageData);\
\
		twoDToImage(invertedImg, "./inverted_apple.jpg");\
		\
\
		int[][] coloredImg = colorFilter(imageData, -75, 30, -30);\
\
		twoDToImage(coloredImg, "./colored_apple.jpg");\
\
		// int[][] allFilters = stretchHorizontally(shrinkVertically(colorFilter(negativeColor(trimBorders(invertImage(imageData), 50)), 200, 20, 40)));\
		// Painting with pixels\
\
    int[][] blankImg = new int[250][250];\
        \
    int[][] randomImg = paintRandomImage(blankImg);\
        \
    twoDToImage(randomImg, "./random_img.jpg");\
\
    // Calling Rectangle Method \
\
    int[] rgba = \{255, 255, 0, 255\};\
        \
    int[][] rectangleImg = paintRectangle(randomImg, 200, 200, 100, 100, getColorIntValFromRGBA(rgba));\
        \
    twoDToImage(rectangleImg, "./rectangle.jpg");\
\
    int[][] generatedRectangles = generateRectangles(randomImg, 1000);\
\
		twoDToImage(generatedRectangles, "./generated_rect.jpg");\
	\}\
  \
	// Image Processing Methods\
	public static int[][] trimBorders(int[][] imageTwoD, int pixelCount) \{\
		// Example Method\
		if (imageTwoD.length > pixelCount * 2 && imageTwoD[0].length > pixelCount * 2) \{\
			int[][] trimmedImg = new int[imageTwoD.length - pixelCount * 2][imageTwoD[0].length - pixelCount * 2];\
			for (int i = 0; i < trimmedImg.length; i++) \{\
				for (int j = 0; j < trimmedImg[i].length; j++) \{\
					trimmedImg[i][j] = imageTwoD[i + pixelCount][j + pixelCount];\
				\}\
			\}\
			return trimmedImg;\
		\} else \{\
			System.out.println("Cannot trim that many pixels from the given image.");\
			return imageTwoD;\
		\}\
	\}\
\
	public static int[][] negativeColor(int[][] imageTwoD) \{\
		// TODO: Fill in the code for this method\
    int[][] negativeImg = new int [imageTwoD.length][imageTwoD[0].length];\
    for (int i = 0; i < imageTwoD.length; i++) \{\
      for (int j = 0; j < imageTwoD[0].length; j++) \{\
        int [] rgba = getRGBAFromPixel(imageTwoD[i][j]);\
        rgba[0] = 255 - rgba[0];\
        rgba[1] = 255 - rgba[1];\
        rgba[2] = 255 - rgba[2];\
        negativeImg[i][j] = getColorIntValFromRGBA(rgba);\
      \}\
    \}\
		return negativeImg;\
	\}\
\
	public static int[][] stretchHorizontally(int[][] imageTwoD) \{\
		// TODO: Fill in the code for this method\
    int[][] horizontalImg = new int[imageTwoD.length][imageTwoD[0].length*2];\
    int width = 0;\
    for(int i = 0; i < imageTwoD.length; i++) \{\
      for(int j =0; j < imageTwoD[i].length; j++) \{\
        width = j*2;\
        horizontalImg[i][width] = imageTwoD[i][j];\
        horizontalImg[i][width+1] = imageTwoD[i][j];\
      \}\
    \}\
		return horizontalImg;\
	\}\
\
	public static int[][] shrinkVertically(int[][] imageTwoD) \{\
		// TODO: Fill in the code for this method\
    int [][] shrinkImg = new int[imageTwoD.length/2][imageTwoD[0].length];\
    for (int i = 0; i < imageTwoD[0].length; i++) \{\
      for (int j = 0; j < imageTwoD.length - 1; j += 2) \{\
        shrinkImg[j/2][i] = imageTwoD[j][i];\
      \}\
    \}\
		return shrinkImg;\
	\}\
\
	public static int[][] invertImage(int[][] imageTwoD) \{\
		// TODO: Fill in the code for this method\
    int[][] invertImg = new int[imageTwoD.length][imageTwoD[0].length];\
    for (int i = 0; i < imageTwoD.length; i++) \{\
      for (int j = 0; j < imageTwoD[i].length; j++) \{\
        invertImg[i][j] = imageTwoD[(imageTwoD.length-1)-i][(imageTwoD[i].length-1)-j];\
      \}\
    \}\
		return invertImg;\
	\}\
\
\
	public static int[][] colorFilter(int[][] imageTwoD, int redChangeValue, int greenChangeValue, int blueChangeValue) \{\
		// TODO: Fill in the code for this method\
    int[][] coloredImg = new int[imageTwoD.length][imageTwoD[0].length];\
    for (int i = 0; i < imageTwoD.length; i++) \{\
      for (int j = 0; j < imageTwoD[i].length; j++) \{\
      int[] rgba = getRGBAFromPixel(imageTwoD[i][j]);\
      int newRed = rgba[0] + redChangeValue;\
      int newGreen = rgba[1] + greenChangeValue; \
      int newBlue = rgba[2] + blueChangeValue;\
\
      newRed = Math.max(0, Math.min(255, newRed));\
      newGreen = Math.max(0, Math.min(255, newGreen));\
      newBlue = Math.max(0, Math.min(255, newBlue));\
\
      rgba[0] = newRed;\
      rgba[1] = newGreen; \
      rgba[2] = newBlue; \
\
      coloredImg[i][j] = getColorIntValFromRGBA(rgba);\
      \}\
    \}\
    twoDToImage(coloredImg, "./colored_image.jpg");\
		return coloredImg;\
	\}\
	// Painting Methods\
	public static int[][] paintRandomImage(int[][] canvas) \{\
		// TODO: Fill in the code for this method\
    Random rand = new Random();\
    for (int i = 0; i < canvas.length; i++) \{\
      for (int j = 0; j < canvas[i].length; j++) \{\
        int randRed = rand.nextInt(256);\
        int randGreen = rand.nextInt(256);\
        int randBlue = rand.nextInt(256); \
\
        int[] rgbaValues = \{randRed, randGreen, randBlue, 255\};\
        canvas[i][j] = getColorIntValFromRGBA(rgbaValues);\
      \}\
    \}\
		return canvas;\
	\}\
	public static int[][] paintRectangle(int[][] canvas, int width, int height, int rowPosition, int colPosition, int color) \{\
		// TODO: Fill in the code for this method\
    for (int i = 0; i < canvas.length; i++) \{\
      for (int j = 0; i < canvas[i].length; j++) \{\
        if (i >= rowPosition && i <= rowPosition + width) \{\
          if (j >= colPosition && j<= colPosition + height) \{\
              canvas[i][j] = color; \
          \}\
        \}\
      \}\
    \}\
    \
		return canvas;\
	\}\
	public static int[][] generateRectangles(int[][] canvas, int numRectangles) \{\
		// TODO: Fill in the code for this method\
   Random ran = new Random(); \
   for (int i = 0; i < canvas.length; i++) \{\
    for (int j = 0; j < canvas[i].length; j++) \{\
      int randomWidth = ran.nextInt(canvas[0].length);\
      int randomHeight = ran.nextInt(canvas.length);\
\
      int randomRowPos = ran.nextInt(canvas.length-randomHeight);\
      int randomColPos = ran.nextInt(canvas[0].length-randomWidth);\
\
      int[] rgba = \{ran.nextInt(256), ran.nextInt(256), ran.nextInt(256), 255\};\
      int randomColor = getColorIntValFromRGBA(rgba);\
\
      canvas = paintRectangle(canvas, randomWidth, randomHeight, randomRowPos, randomColPos, randomColor);\
\
    \}\
   \}\
		return canvas;\
	\}\
	// Utility Methods\
	public static int[][] imgToTwoD(String inputFileOrLink) \{\
		try \{\
			BufferedImage image = null;\
			if (inputFileOrLink.substring(0, 4).toLowerCase().equals("http")) \{\
				URL imageUrl = new URL(inputFileOrLink);\
				image = ImageIO.read(imageUrl);\
				if (image == null) \{\
					System.out.println("Failed to get image from provided URL.");\
				\}\
			\} else \{\
				image = ImageIO.read(new File(inputFileOrLink));\
			\}\
			int imgRows = image.getHeight();\
			int imgCols = image.getWidth();\
			int[][] pixelData = new int[imgRows][imgCols];\
			for (int i = 0; i < imgRows; i++) \{\
				for (int j = 0; j < imgCols; j++) \{\
					pixelData[i][j] = image.getRGB(j, i);\
				\}\
			\}\
			return pixelData;\
		\} catch (Exception e) \{\
			System.out.println("Failed to load image: " + e.getLocalizedMessage());\
			return null;\
		\}\
	\}\
	public static void twoDToImage(int[][] imgData, String fileName) \{\
		try \{\
			int imgRows = imgData.length;\
			int imgCols = imgData[0].length;\
			BufferedImage result = new BufferedImage(imgCols, imgRows, BufferedImage.TYPE_INT_RGB);\
			for (int i = 0; i < imgRows; i++) \{\
				for (int j = 0; j < imgCols; j++) \{\
					result.setRGB(j, i, imgData[i][j]);\
				\}\
			\}\
			File output = new File(fileName);\
			ImageIO.write(result, "jpg", output);\
		\} catch (Exception e) \{\
			System.out.println("Failed to save image: " + e.getLocalizedMessage());\
		\}\
	\}\
	public static int[] getRGBAFromPixel(int pixelColorValue) \{\
		Color pixelColor = new Color(pixelColorValue);\
		return new int[] \{ pixelColor.getRed(), pixelColor.getGreen(), pixelColor.getBlue(), pixelColor.getAlpha() \};\
	\}\
	public static int getColorIntValFromRGBA(int[] colorData) \{\
		if (colorData.length == 4) \{\
			Color color = new Color(colorData[0], colorData[1], colorData[2], colorData[3]);\
			return color.getRGB();\
		\} else \{\
			System.out.println("Incorrect number of elements in RGBA array.");\
			return -1;\
		\}\
	\}\
	public static void viewImageData(int[][] imageTwoD) \{\
		if (imageTwoD.length > 3 && imageTwoD[0].length > 3) \{\
			int[][] rawPixels = new int[3][3];\
			for (int i = 0; i < 3; i++) \{\
				for (int j = 0; j < 3; j++) \{\
					rawPixels[i][j] = imageTwoD[i][j];\
				\}\
			\}\
			System.out.println("Raw pixel data from the top left corner.");\
			System.out.print(Arrays.deepToString(rawPixels).replace("],", "],\\n") + "\\n");\
			int[][][] rgbPixels = new int[3][3][4];\
			for (int i = 0; i < 3; i++) \{\
				for (int j = 0; j < 3; j++) \{\
					rgbPixels[i][j] = getRGBAFromPixel(imageTwoD[i][j]);\
				\}\
			\}\
			System.out.println();\
			System.out.println("Extracted RGBA pixel data from top the left corner.");\
			for (int[][] row : rgbPixels) \{\
				System.out.print(Arrays.deepToString(row) + System.lineSeparator());\
			\}\
		\} else \{\
			System.out.println("The image is not large enough to extract 9 pixels from the top left corner");\
		\}\
	\}\
\}}