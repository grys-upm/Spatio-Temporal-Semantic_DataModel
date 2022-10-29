# Spatio-Temporal-Semantic Data Model for Precision Agriculture - Set of Schemas
Set of Json Schemas modelling observations from sensors or devices, collars from livestock and State Vectors of vehicles.

The model includes information associated with each dimension for each of the data sets:



![DataModel_Schemas](https://user-images.githubusercontent.com/60104587/198826413-fb53bc4c-18d2-4c85-9898-944f2e87f7af.png)



The observation dataset collects the information related to the measurements captured by sensors installed in devices. The information is modelled for different cases: (i) Observation captured by one sensor; (ii) Several observations captured by the same sensor installed in a device; (iii) Set of observations captured by several sensors installed in a single device.

At the same time, simplified versions of each of the schemes are included in the model, to facilitate their completion and sending from sensors with more limited resources.

The set of collars collects information from temperature sensors, accelerometers and the detection of anomalies embedded in a collar installed on the cattle's neck. The set of schemes contemplates the possibility of filling in data associated with a single instant of time or aggregated data.

The set of vehicle state vectors provides information on vehicle orientation, linear velocity and battery conditions. The use of this type of modelling is especially useful for solutions that integrate the use of Unmanned Aerial Vehicles (UAVs).


