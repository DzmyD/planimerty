# ADT Parallelogram
> [!NOTE]
> Tris ADT is not completed.
> You can read more about parallelogram [here](parallelogram.md).
## Data
Variables ***ab_side***, ***bc_side***, ***cd_side***, ***ad_side***, ***ac_side*** and ***bd_state*** are real numbers, indicating length and greater than $0$. Variables ***bad_angle***, ***abc_angle***, ***bcd_angle***, ***adc_angle***, ***cad_angle***, ***cab_angle***, ***acb_angle***, ***acd_angle***, ***abd_angle***, ***cbd_angle***, ***adb_angle*** and ***bdc_angle*** are real numbers, indicating degrees, greater than $0$<sup>o</sup> and less $180$<sup>o</sup>. Every variables *can supplement* missing variables by inside functions if it is possible.

Variables ***ab_side_state***, ***bc_side_state***, ***cd_side_state***, ***ad_side_state***, ***ac_side_state***, ***bd_side_state***, ***bad_side_state***, ***abc_angle_state***, ***bcd_angle_state***, ***adc_angle_state***, ***cad_angle_state***, ***cab_angle_state***, ***acb_angle_state***, ***acd_angle_state***, ***abd_angle_state***, ***cbd_angle_state***, ***adb_angle_state*** and ***bdc_angle_state*** are boolean. False, if a user used default values during initialization respectively.
## Operations
* Constructor
  * Input: $AB$, $BC$, $CD$, $AD$, $AC$, $BD$, $BAD$, $ABC$, $BCD$, $ADC$, $CAD$, $CAB$, $ACB$, $ACD$, $ABD$, $CBD$, $ADB$ and $BDC$. By default, Every lines are 1, angles $BAD$, $ABC$, $BCD$, $ADC$ are 90<sup>o</sup> and angles $CAD$, $CAB$, $ACB$, $ACD$, $ABD$, $CBD$, $ADB$, $BDC$ are 45<sup>o</sup>
  * Precondition:
    
        AB, BC, CD, AD, AC, BD > 0
      
        0 < BAD, ABC, BCD, ADC, CAD, CAB, ACB, ACD, ABD, CBD, ADB, BDC < 180
        
        CAB + CAD == BAD
        
        CBD + ABD == ABC
        
        ACD + ACB == BCD
        
        BDC + ADB == ADC

        AB == BC, BC == AD

        BAD == BCD, ABC == ACD

        CBD == ADB, ABD == BDC, ACB == CAD, BAC == ACD

        // add check of diagonals to sides

        // add check angles near parallel sides and one secant line

        // add check the property "Adjacent angles are supplementary"
    
  * Operation: if the value was determined and it's correct, then ...***_state*** variable is $true$, else ...***_state*** is $false$. Every variables are assigned a new value or default value respectively. Every default variables trying to change their values. For example, There are diagonals.
  * Postcondition: -
  * Output: -
----
* getSide
  * Output: the massive of all sides values **[AB, BC, CD, AD, AC, BD]**.
* getDiagonal
  * Output: the massive of all diagonals values **[AC, BD]**
* getAngle
  * Output: the massive of all angles values **[BAD, ABC, BCD, ADC, CAD, CAB, ACB, ACD, ABD, CBD, ADB, BDC]**
* getSideState
  * Output: the boolean massive of all sides values **[AB, BC, CD, AD, AC, BD]**.
* getDiagonalState
  * Output: the boolean massive of all diagonals values **[AC, BD]**
* getAngleState
  * Output: the boolean massive of all angles values **[BAD, ABC, BCD, ADC, CAD, CAB, ACB, ACD, ABD, CBD, ADB, BDC]**
----
* getSideAB
  * Output: the value of ***ab_side***
* getSideBC
  * Output: the value of ***bc_side***
* getSideCD
  * Output: the value of ***cd_side***
* getSideAD
  * Output: the value of ***ad_side***
* getSideAC
  * Output: the value of ***ac_side***
* getSideBD
  * Output: the value of ***bd_side***
----
* getSideStateAB
  * Output: the value of ***ab_side_state***
* getSideStateBC
  * Output: the value of ***bc_side_state***
* getSideStateCD
  * Output: the value of ***cd_side_state***
* getSideStateAD
  * Output: the value of ***ad_side_state***
* getSideStateAC
  * Output: the value of ***ac_side_state***
* getSideStateBD
  * Output: the value of ***bd_side_state***
----
* getAngleBAD
  * Output: the value of ***bad_angle***
* getAngleABC
  * Output: the value of ***abc_angle***
* getAngleBCD
  * Output: the value of ***bcd_angle***
* getAngleADC
  * Output: the value of ***adc_angle***
* getAngleCAD
  * Output: the value of ***cad_angle***
* getAngleCAB
  * Output: the value of ***cab_angle***
* getAngleACB
  * Output: the value of ***acb_angle***
* getAngleACD
  * Output: the value of ***acd_angle***
* getAngleABD
  * Output: the value of ***abd_angle***
* getAngleCBD
  * Output: the value of ***cbd_angle***
* getAngleADB
  * Output: the value of ***adb_angle***
* getAnglebdc
  * Output: the value of ***bdc_angle***
----
* getAngleStateBAD
  * Output: the value of ***bad_angle_state***
* getAngleStateABC
  * Output: the value of ***abc_angle_state***
* getAngleStateBCD
  * Output: the value of ***bcd_angle_state***
* getAngleStateADC
  * Output: the value of ***adc_angle_state***
* getAngleStateCAD
  * Output: the value of ***cad_angle_state***
* getAngleStateCAB
  * Output: the value of ***cab_angle_state***
* getAngleStateACB
  * Output: the value of ***acb_angle_state***
* getAngleStateACD
  * Output: the value of ***acd_angle_state***
* getAngleStateABD
  * Output: the value of ***abd_angle_state***
* getAngleStateCBD
  * Output: the value of ***cbd_angle_state***
* getAngleStateADB
  * Output: the value of ***adb_angle_state***
* getAngleStateBDC
  * Output: the value of ***bdc_angle_state***

// add set functions
