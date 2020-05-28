# Fragment_Android
Here we are describing the Fragment in details and Lifecycle

# Fragment Introduction 

- Android Fragment is the part of activity, it is also known as sub-activity. There can be more than one fragment in an activity. Fragments represent multiple screen inside one activity
- Android fragment lifecycle is affected by activity lifecycle because fragments are included in activity.

# Method	Description
1)	onAttach(Activity)	it is called only once when it is attached with activity.
2)	onCreate(Bundle)	It is used to initialize the fragment.
3)	onCreateView(LayoutInflater, ViewGroup, Bundle)	creates and returns view hierarchy.
4)	onActivityCreated(Bundle)	It is invoked after the completion of onCreate() method.
5)	onViewStateRestored(Bundle)	It provides information to the fragment that all the saved state of fragment view hierarchy has been restored.
6)	onStart()	makes the fragment visible.
7)	onResume()	makes the fragment interactive.
8)	onPause()	is called when fragment is no longer interactive.
9)	onStop()	is called when fragment is no longer visible.
10)	onDestroyView()	allows the fragment to clean up resources.
11)	onDestroy()	allows the fragment to do final clean up of fragment state.
12)	onDetach()	It is called immediately prior to the fragment no longer being associated with its activity.

# Send Data to Fragment From Another Activity

How to Pass Data-  Activity to Fragment

- Two ways to do it
  1. Bundle object 
  2. Fragment Object
  
Which one is better? 
- Bundle object is use for Primitive type data type and its better to Fragment Object
- Fragement object is use fot Non-Primitive data type and Primitive data type. 



- 
