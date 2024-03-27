“ COUNTRY CODE”

Seethalakshmi Achi college for Women

NM ID	
NAME 261FB186E7VD65VA2AB42AB10EFC309A VEERALAKSHMI A

Trainer Name R.Umamaheshwari

                    ABSTRACT               	
                                                                  
A country code is a numerical or alphanumeric code used in telecommunication to identify a specific country or group of countries. These codes are essential for international communication and are used in various contexts, such as international direct dialing (IDD) and routing telephone calls to destinations outside the caller’s country. A country code is a short alphanumeric identification used for countries and dependent areas in various contexts. Here are some key points about country codes:

Telephone Country Codes (ISD Codes):
o In telecommunication, a country code, also known as an international subscriber dialing (ISD) code, is a telephone number prefix used for international direct dialing (IDD). o When making international calls, you typically dial the country code before the actual phone number to route the call to the correct country. o For example, the country code for the United States is +1, so to call a U.S. number from another country, you would dial +1 followed by the U.S. phone number. 2. ISO Country Codes: o ISO 3166-1 defines codes for the representation of names of countries and their subdivisions. o These codes are used in data processing, communications, and various international contexts. o Each country is assigned a unique two-letter or three-letter code. o For instance:  Afghanistan has the ISO code AF.  Albania has the ISO code AL.  Algeria has the ISO code DZ. 3. Destination Routing and Data Processing: o Country codes play a crucial role in destination routing for telephone calls, internet domains, and other communication systems. o They help ensure that data and communications are directed to the correct country or region.

                                          INDEX
Sr. No. Table of Contents Page No. 1 Chapter 1: Introduction 4 2 Chapter 2: Services and Tools Required 6 3 Chapter 3: Project Architecture 7 4 Chapter 4: Modeling and Result 9 5 Conclusion 18 6 Future Scope 19 7 References 20 8 Links 21

 

CHAPTER 1 INTRODUCTION 1.1 Problem Statement Back in 2018 and 2019, during RIPE 77 and RIPE 78, we presented about the lack of a clear definition for the Country Code attribute. This attribute is present in both the RIPE Database and the Extended Delegated Statistics for the Internet number resources that the RIPE NCC allocates and assigns to LIRs and their End Users. In general, the Country Code refers to the country where the network is located. But, what does that actually mean? Well, it's complicated.

1.2 Proposed Solution The Country Code for resource objects in the RIPE Database will remain as is, maintained by the resource holder who decides the criteria. A new attribute will be added to the ORGANISATION object, with the Country Code for the country in which the resource holder is legally based. This attribute will be maintained by the RIPE NCC. This new Country Code attribute will also be reflected in the Extended Delegated Statistics. Hence, this file will show in which country the resource holder is legally base. 1.3 FEATURES

• Country codes are prefixes used for international direct calling. Think of them as digital passports for virtual communication.

• When you dial an international number, you start with the country code. It acts as an exit from your national numbering system and places you into the international one.

1.4 Advantages Using codes saves time and avoids errors as instead of using a country’s name (which will change depending on the language being used), we can use a combination of letters and/or numbers that are understood all over the world.

1.5 scope Afghanistan (AF): 1.6 Country Code: 93 1.7 Population: Approximately 29.1 million 1.8 Area: 647,500 square kilometers 1.9 GDP: $20.65 billion1 Albania (AL): 1.10 Country Code: 355 1.11 Population: Around 2.98 million 1.12 Area: 28,748 square kilometers 1.13 GDP: $12.8 billion1 Algeria (DZ): 1.14 Country Code: 213 1.15 Population: About 34.6 million 1.16 Area: 2,381,740 square kilometers 1.17 GDP: $215.7 billion

CHAPTER 2 SERVICES AND TOOLS REQUIRED 2.1 Services Used

CountryCode.org: This website provides a comprehensive list of country codes, including instructions on how to call each country using its specific code. You can find details like area codes, ISO country codes, and even information about electrical outlets and phone jacks in different parts of the world. Feel free to visit .
ISO 3166 Country Codes: The International Organization for Standardization (ISO) maintains a set of country codes known as ISO 3166. These codes are used globally and allow free-of-charge use.
2.2 Tools and Software used Tools: • PowerBI: The main tool for this project is PowerBI, which will be used to create interactive dashboards for real-time data visualization.

• Power Query: This is a data connection technology that enables you to discover, connect, combine, and refine data across a wide variety of sources. Software Requirements: • PowerBI Desktop: This is a Windows application that you can use to create reports and publish them to PowerBI.

• PowerBI Service: This is an online SaaS (Software as a Service) service that you use to publish reports, create new dashboards, and share insights.

• PowerBI Mobile: This is a mobile application that you can use to access your reports and dashboards on the go. CHAPTER 3 PROJECT ARCHITECTURE 3.1 Architecture

Here’s a high-level architecture for the project:

ISO 3166-1:
o ISO 3166-1 stands for “Codes for the representation of names of countries and their subdivisions – Part 1: Country codes.” o It is a standard published by the International Organization for Standardization (ISO). o ISO 3166-1 defines three sets of country codes:  Alpha-2 Codes: These are two-letter country codes and are the most widely used. They are commonly associated with country code top-level domains (such as .us, .uk, etc.) on the Internet.  Alpha-3 Codes: These are three-letter country codes that allow for better visual association between the codes and country names compared to alpha-2 codes.  Numeric Codes: These are three-digit country codes that are identical to those maintained by the United Nations Statistics Division. They are useful for systems using non-Latin scripts. o The alphabetic country codes were first included in ISO 3166 in 1974, and the numeric country codes were added in 1981. o ISO 3166-1 is implemented in other standards and used by international organizations to facilitate the exchange of goods and information. o It’s important to note that while ISO 3166-1 is widely used, it’s not the only standard for country codes. Other codes used by international organizations may differ from ISO 3166-1 codes. o Criteria for inclusion: Codes are assigned to 249 countries, territories, or areas of geographical interest based on specific criteria, including UN membership and specialized agency participation.

Practical Application:
o When you see a domain like .jp (Japan), .fr (France), or .in (India), these correspond to ISO 3166-1 alpha-2 codes. o For instance, Japan’s alpha-2 code is “JP”, France’s is “FR”, and India’s is "IN"2.

CHAPTER 4 MODELING AND RESULT

Manage relationship The “disp” file will be used as the main connector as it contains most key identifier (account id, client id and disp id) which can be used to relates the 8 data files together. The “district” file is use to link the client profile geographically with “district id”

Modelling for country code

Replacing values Set some fields to English for easy understanding, we replace values to English with the Power Query Editor.

DASHBOARD

CONCLUSION

ISO 3166-1 alpha-2: These are two-letter country codes and are the most widely used. They are prominently used for country code top-level domains on the Internet (with a few exceptions). For example, the United States has the alpha-2 code "US"1.
ISO 3166-1 alpha-3: These are three-letter country codes that allow better visual association between the codes and country names compared to the alpha-2 codes. For instance, India’s alpha-3 code is "IND"1.
ISO 3166-1 numeric: These are three-digit country codes that are identical to those developed and maintained by the United Nations Statistics Division. They offer the advantage of script independence, making them useful for systems using non-Latin scripts. The numeric country codes were first included in ISO 3166 in 1981.
These codes facilitate the exchange of goods and information internationally. However, ISO 3166-1 is not the only standard for country codes. Other codes used by international organizations may be partly or totally incompatible with ISO 3166-11. For example, the European Union (EU) is not formally included in ISO 3166-1, but the code “EU” is reserved for practical identification purposes within the framework of ISO 3166-11. In summary, ISO 3166-1 provides standardized country codes that play a crucial role in global communication and coordination.

                            FUTURE SCOPE
The future scope of this project is vast. With the advent of advanced analytics and machine learning, PowerBI can be leveraged to predict future trends based on historical data. Integrating these predictive analytics into the project could enable the ban

REFERANCE • Power BI’s filled map uses the Bing Maps API to get geocoded locations and outlines. When specifying country or region codes, it’s crucial to use the full name of these regions rather than acronyms. • For example, instead of using “NA” for North America, use “North America” as the value. Similarly, use “EMEA” for Europe, Middle East, and Africa, “APAC” for Asia-Pacific, and “LAM” for Latin America.

Link
