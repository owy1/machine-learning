# machine-learning

For the imperfect data assignment I have downloaded Building Permits: Current from data.seattle.gov

https://dev.socrata.com/foundry/data.seattle.gov/i5jq-ms7b

I choose this because the data has good description (unlike some of those in transportation) 
and > 200 rows.  I just realized how bad shape some of these data is. I am joining OpenSeattle user testing group
 and maybe I can help improve data usability.   
Dataset is provided by Seattle Department of Construction and Inspections.  
It lists building permits issued in the past five years or currently in progress.

The dataset has 55.7K rows and 20 columns.  The column description is as follow:

1.  Application/Permit Number, plain text, 
The tracking number used to refer to this application or permit record in 
various Seattle DCI tracking systems.

2.  Permit Type, plain text,    
Type of activity covered by the permit.

3.  Address, plain text, 
Street address of the work site.

4.  Description, plain text, 
Brief description of the work that will be done under this permit. This is subject
 to change prior to issuance of the permit, but generally more stable if an issue 
 date exists. Very long descriptions have been truncated.

5.  Category, plain text, 
    
The broad category of use or occupancy for the building where work is proposed. 
Valid choices are Commercial, Industrial, Institutional, Multifamily, and Single 
Family/Duplex. Mixed use structures are generally represented as Commercial.

6.  Action Type, plain text, 
Subclassification for type of work being proposed. Valid choices will vary depending on the permit type.

7.  Work Type, plain text, 
    
An indicator of the complexity of the project proposed. Easier projects can be issued 
without plan review; more complex projects generally require plan submittal and review. 

8.  Value, financial,
The value of the work being proposed based on fair market value (parts plus labor). The value 
displayed (if any) represents the best available information to date, and is subject to change 
if the project is modified. Value is not collected for all permit types.

9.  Applicant Name, plain text, 
The name of the person or company listed on the application as the “primary applicant”. 
This may be the property owner, contractor, design professional, or other type of agent.

10. Application Date, date and time,
The date the application was accepted as a complete submittal. If no Application Date 
exists this generally means the application is in a very early stage.

11. Issue Date, date and time, 
The date the application was issued as a valid permit. If an Application Date exists 
but no Issue Date exists, this generally means the application is still under review.

12. Final Date, date and time,
The date the permit had all its inspections completed. If an Issue Date exists but no 
Final Date exists, this generally means the permit is still under inspection.

13. Expiration Date, date and time, 
The date the application is due to expire. Generally, this is the date by which work is 
supposed to be completed (baring renewals or further extensions). If no Expiration Date 
exists, this generally means the application is has not been issued yet.

14. Status, plain text, 
    
The current status in the application/review/inspection lifecycle. Indicates the 
last process step that was fully completed.

15. Contractor, plain text, 
Contractor(s) who are associated with this permit.

16. Permit and Complaint Status URL, url,
Link to view full details and current status information about this permit at Seattle DCI's website.

17. Master Use Permit, plain text, 
A Master Use/Land Use Permit is required before some building permits to make decisions about 
site-specific factors of the project, such as environmental impacts or neighborhood design considerations.

18. Latitude, number, 
    
Latitude of the worksite where permit activity occurs. May be missing for a small 
number of permits considered "Unaddressable"

19. Longitude, number,
Longitude of the worksite where permit activity occurs. May be missing for a small 
number of permits considered "Unaddressable"

20. Location, array, 
Mapping coordinates for the permit address.

