This is a classifier model for the famous Titanic dataset
It includes:																																																				1.Extraction of title from name to include effects of class system as Title
	2.Combining SibSp and Parch as FamilySize
	3.IsAlone col (using FamilySize)
	4. Dividing fare with FamilySize as same ticket no are given to multiple people of the same family and fare is added for all
	5.NaN values filled using median for numeric cols and mode for categorical cols
	6.Encoding of categorical cols using .replace()
Logistic Regression model to classify.
