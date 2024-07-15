# Football-Analysis-with-Yolov5s

• Performed real-time analysis, providing metrics for ball control, possession, distance covered and avg speed of players.
• Fine tuned Yolov5s model to detect Players, Referees, and the Ball using annotated image data from Roboflow.
• Grouped players into respective teams by extracting their pixel colors and applying k-Means Clustering (n=2).
• Performed Ball interpolation using the ’interpolate’ and ’bfill’ functions from the Pandas framework.
• Applied cv2 functions ’goodFeaturesToTrack’ and ’calcOpticalFlowPyrLK’ on top masked pixels to estimate camera
movement. And performed perspective transformation using ’pointPolygonTest’ and ’getPerspectiveTransform’
