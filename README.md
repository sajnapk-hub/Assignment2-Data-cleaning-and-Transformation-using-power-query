# Assignment2-Data-cleaning-and-Transformation-using-power-query
checked price column and found null values handeled these missing values by replacing them with median price
checked category column and found missing values replaced with them "Unknown"
identified inconsistent text format present in the "product name"column and applied trim,capitelization and clean format
identified spelling mistake in the catogory column and corrected it
checked the data set and removed duplicates using remove rows option in the power query
splitted product id column intotwo columns(1.manufacturing date and 2.country code)
merged the columnbrand name andproduct name into a single column named "product brand"
formatted data type of price column to currency format
applied data bar using conditional format in the price column
created a custom rule in the category column to highlight cells where the category is "electronics"
