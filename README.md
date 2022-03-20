# EDA_for_Kiva
Education project for Skillbox

### Description
Kiva is a non-profit organization that helps in more than 80 countries around the world to receive funding for plausible projects and needs.

Kiva's slogan is "Take a loan, change your life".

Basically, Kiva's activities are related to the coverage of the population, as well as the financing of social projects. 
A list of applications, solutions and countries in need of funding can be viewed at kiva.org. 
These are topics related in one way or another to agriculture, nutrition, health and hygiene, retail and small business support. 

### Goal

Kiva wants to make the best use of the money raised. They are primarily interested in tangible findings and recommendations that will enable the organization to work more effectively and better understand the specific needs and levels of poverty in different countries and regions.

### Task

1. We check how clean the available data is, that is, it is prone to outliers, missing and invalid values.
2. We study the main demographic characteristics of people who use Kiva. What regions and countries are they from? What is the gender profile of borrowers?
3. We investigate for what purposes people need funds and what amounts they ask for. We study sectors of the economy, types of activities and draw conclusions about how things are in each of them.
4. How long do borrowers have to wait for an application to be fully funded? Some people on the platform have been known to ask for emergency loans. 

### Data description

kiva_loans is a dataset that contains most of the information about loans:

    id is a unique identifier for the loan.
    funded_amount - The amount paid by Kiva to the field agent (USD).
    loan_amount - the amount paid by the field agent to the borrower (USD).
    sector — sector of loan use.
    activity is a more granular category.
    use — purpose of using the loan amount.
    country_code — ISO country code of the country in which the loan was issued.
    country — the full name of the country in which the loan was issued.
    posted_time - the time at which the order was published on Kiva.
    disbursed_time - the time when the loan agent disbursed the amount to the borrower.
    funded_time - the time when the application is fully funded by creditors.
    term_in_months — term for which the loan was issued in months.
    lender_count is the total number of lenders who contributed to this loan.
    loaner_genders - comma separated letters M, F, where each instance represents one male/female in the group.

kiva_mpi_region_locations - Dataset of regions with MPI: (Global Multidimensional Poverty Index - global poverty index) of a number of regions (subnational) in the world. The larger this value, the higher the poverty rate in the corresponding region.

    country - country.
    region — region in the country.
    world_region - part of the world.
    MPI is a multidimensional poverty index.
    geo - coordinates (latitude, longitude). 


### Conclusion

First of all, it is necessary to note the very important and significant role of the Kiva platform and its community. For a large number of people in very different parts of the world, Kiva plays a critical role in supporting operations and business activities, actively complementing, and often acting as, the private banking sector.
   1. More than ever, it's worth paying attention to the Kiva community and directing efforts to support those most in need! Such requests can be displayed in separate categories and include appeals in their headings: Urgent needs, Urgent, Funding expires.
   2. If possible, it is worth dividing applications from poor countries into small and short loans, each of which will be another small step in a big deal.
   3. When it comes to opportunities for human development, the boundaries between men and women are blurred. It is worth striving to ensure equal access to finance for women and men, and pay attention to those countries and regions where this balance is still out of whack. For example, for countries such as Samoa, Liberia, Togo, first display loans from men on the main page.
   4. Priority should be given to applications aimed at developing industries with high added value and stimulating production, as they are the driving force and begin to involve other industries along the chain. Namely, construction, manufacturing, light industry.
   5. There is still a high proportion of applications aimed at satisfying the most basic human needs. Such requests should not go unnoticed, but be the first candidates on the main page. Such situations are unacceptable when, for example, in Nigeria, people wait for vitally important clean water for 10 days.
   6. For a number of regions and countries of presence, such as South Asia, in particular Pakistan and India, there are excellent prospects for expanding the presence and activities of the Kiva community.
   7. It is not uncommon for there to be inequalities between countries, such as long waiting times for funding for some applications with very small amounts. 
