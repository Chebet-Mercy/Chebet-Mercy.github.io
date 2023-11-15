## TBI-Traumatic-Brain-Injury / project page

**Project description:**

Brain Injury Awareness Month, observed each March, was established 3 decades ago to educate the public about the incidence of brain injury and the needs of persons with brain injuries and their families. Traumatic Brain Injury (TBI) is caused by a bump, blow, or jolt to the head, or penetrating head injury which can lead to short- or long-term changes affecting thinking, sensation, language, or emotion.

The goal of this project is to **spread awareness for just how common TBIs are - both in civilian and military populations**. 

More details can be found at the [Brain Injury Association Website](https://www.biausa.org/public-affairs/public-awareness/brain-injury-awareness).

### Data Dictionary

#### `tbi_age.csv`

|variable         |class     |description |
|:----------------|:---------|:-----------|
|age_group        |character | Age group |
|type             |character | Type of measure |
|injury_mechanism |character | Injury mechanism |
|number_est       |double    | Estimated observed cases in 2014 |
|rate_est         |double    | Rate/100,000 in 2014 |

 #### `tbi_year.csv`

|variable         |class     |description |
|:----------------|:---------|:-----------|
|injury_mechanism |character | Injury mechanism |
|type             |character | Type of measure |
|year             |character | Year |
|rate_est         |double    | Rate/100,000 in 2014 |
|number_est       |integer   | Estimated observed cases in each year |

#### `tbi_military.csv`

|variable  |class     |description |
|:---------|:---------|:-----------|
|service   |character | Military branch |
|component |character | Military component (active, guard, reserve) |
|severity  |character | Severity/type of TBI |
|diagnosed |double    | Number diagnosed |
|year      |integer   | Year for observation|

### 3. Data Analysis and Manipulation of the data
The TBI data was analysed and manipulated using SQL

For more details see [TBI SQL Script](https://github.com/Chebet-Mercy/TBI-Traumatic-Brain-Injury/blob/main/TBI%20script.sql/).

### 4. Presentation of the TBI Data
The Final presentation of TBI  [Traumatic Brain Injury](https://github.com/Chebet-Mercy/Chebet-Mercy.github.io/blob/master/Traumatic%20Brain%20Injury.pdf)

