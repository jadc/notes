# Electrochemistry

!> These notes are unfinished and subject to change.

?> In most examples, states of substances will not be written; remember that they are still required in all equations in an actual examination.

---

# Essentials
**Oxidation**  
Complete or partial loss of electrons.  
(or, gain of oxygen)

**Reduction**  
Complete or partial gain of electrons.  
(or, loss of oxygen)

**Reduction Oxidation (Redox) Reaction**  
Electrons are transferred between reactants.  
All oxidation reactions are accompanied by reduction reactions.

## Half Reactions
Separation of net redox reactions into two separate oxidation and reduction reactions.

Always write the $e^-$ on the side with the ~~most positive charge~~.

##### Oxidation Half Reaction Example
$\textrm{Mg} \longrightarrow \textrm{Mg}^{2+} + 2e^-$

~~$e^-$ always on the **right** of the arrow.~~

##### Reduction Half Reaction Example
$\textrm{S} + 2e^- \longrightarrow \textrm{S}^{2-}$

~~$e^-$ always on the **left** of the arrow.~~

#### Bonus
I personally remember this by thinking *\"Reduction left the electrons.\"*  
No fun abbreviation here, just remember it. ![4HEad](https://cdn.frankerfacez.com/emoticon/128247/1)

## Agents
The substance that makes a reaction possible is the agent of that reaction.

For instance, in a redox reaction,
* the substance that donates the electrons (oxidizes) is the **reducing agent (RA)**.
* the substance that receives the electrons (reduces) is the **oxidizing agent (OA)**.

In other words, a substance is the ~~opposite agent to what it did~~.

## Spectator Ion
An ion that undergoes no electron transfer.  
*e.g. $\textrm{NO}_3^-$ in the upcoming section*

# Determing the Redox of an Equation
1. Identify and ignore any spectator ions.
2. Determine what has gained electrons, and what has lost electrons.
   1. Pay attention to quantities (coefficients and subscripts) as the amount of electrons gained/lost will be multiplied by them.
      *e.g. $\textrm{Br}_2 + 2e^- \longrightarrow 2\textrm{Br}^-$, $2\textrm{Br}^-$ needs 2 electrons to be neutral.*
3. Write out the equation showing ions.  
   This can be done by ~~cancelling the equal electrons~~ between both half reactions.
4. Verify that the sum of charges of all ions on both sides remains constant. (if not, it isn't truly redox)

#### Example Problem
*What is oxidized and what is reduced in the following reaction?*

$2\textrm{AgNO}_3 + \textrm{Cu} \longrightarrow \textrm{Cu} ( \textrm{NO}_3 )_2 + 2\textrm{Ag}$

1. $\textrm{NO}_3^-$ is a spectator ion. Ignore it.  

2. $2\textrm{Ag}^+ + 2e^- \longrightarrow 2\textrm{Ag}$ (or $2(\textrm{Ag}^+ + e^- \longrightarrow \textrm{Ag})$)  
   *($\textrm{Ag}$ went from missing 1 electron to being balanced, but since there are 2 of them on both sides, 2 electrons were actually missing)*

   $\textrm{Cu} \longrightarrow \textrm{Cu}^{2+} + 2e^-$

3. $2\textrm{Ag}^+ + \textrm{Cu} \longrightarrow 2\textrm{Ag} + \textrm{Cu}^{2+}$

4.

The following tables are simply the charges of each ion in the equation.

| $2\textrm{Ag}^+$ | $+$ | $\textrm{Cu}$ | $\longrightarrow$ | $2\textrm{Ag}$ | $+$ | $\textrm{Cu}^{2+}$ |
| --- | --- | --- | --- | --- | --- | --- |
| $2+$ | $+$ | $0$ | $=$ | $0$ | $+$ | $2+$ |

They are equal on both sides, therefore the redox reaction is verified.

## Inequal Net Charges
Sometimes the net charges of both sides of the equation will not be equal, despite being a redox reaction.

In these cases, multiply both half reactions by whatever you need to so that the net electrons of both half reactions are equal.

#### Example Problem
$\textrm{Al} + \textrm{Cd}(\textrm{NO}_3)_2 \longrightarrow \textrm{Al}(\textrm{NO}_3)_3 + \textrm{Cd}$

1. $\textrm{NO}_3^-$ is a spectator ion. Ignore it.  

2. $\textrm{Al} \longrightarrow \textrm{Al}^{3+} + 3e^-$  
   $\textrm{Cd}^{2+} + 2e^- \longrightarrow \textrm{Cd}$

   Issue: The electrons of both equations do not cancel with each other.  
   Solution: Multiply each entire half reaction by something so that the electrons are equal and can cancel.

   $2(\textrm{Al} \longrightarrow \textrm{Al}^{3+} + 3e^-)$  
   $3(\textrm{Cd}^{2+} + 2e^- \longrightarrow \textrm{Cd})$

   $2\textrm{Al} \longrightarrow 2\textrm{Al}^{3+} + 6e^-$  
   $3\textrm{Cd}^{2+} + 6e^- \longrightarrow 3\textrm{Cd}$

   Now both half reactions have $6e^-$.

3. $2\textrm{Al} + 3\textrm{Cd}^{2+} \longrightarrow 2\textrm{Al}^{3+} + 3\textrm{Cd}$  
   Net charge is constant: $0 + +6 = +6 + 0$

## Don't Be Fooled By Compounds
Always separate compounds before determining if there was an electron transfer.

#### Example Problem
$\textrm{Pb}^{2+} + 2\textrm{I}^- \longrightarrow \textrm{PbI}_2$

Seems like electrons were transferred, but separate the elements in the compound...

$\textrm{Pb}^{2+} + 2\textrm{I}^- \longrightarrow \textrm{Pb}^{2+} + 2\textrm{I}^-$

There was no transfer! Not redox.



# Oxidation Numbers
Oxidation numbers are like a fake/virtual charge, since molecules have no charges, and polyatomic ions only have charges for the entire ion, not individual elements. Due to these factors, we need to "make up" a charge.

Oxidation numbers are a positive or negative number assigned to an atom in a molecule or polyatomic ion based primarily on electronegativities. It is the charge an atom *would have*, since electrons are inequally shared, favoring the element with the greater electronegativity.

## Steps
1. Determine the charge on the entire compound. The net charge of all elements in the compound must equal this value.
   1. For molecular compounds, this is zero.
   2. For polyatomic ions, it depends, so use your data booklet.
2. Identify and state any exceptions. [*(see the next section)*](#Exceptions)
3. The element with the highest electronegativity has an oxidation number equal to its ionic charge. (data booklet)
4. For all previous and future elements, multiply the oxidation number by the quantity of an element.  
   *This is not a new oxidation number value;* this value is solely used for calculating the net charge.
5. Do one of the two options below on any remaining elements to ultimately reach the desired net charge.
   1. The element with the next highest electronegativity has an oxidation number equal to its ionic charge. (data booklet)
   2. The oxidation number is any positive or negative value that causes the net charge to be the desired value.  

## Exceptions

* **Atoms = $0$**  
  All atoms (monotomic, diatomic, or polyatomic) have an oxidation number equal to their charge--zero.

* **Ions = Charge**  
  All ~~monatomic/simple~~ ions have an oxidation number equal to their charge.

* **Group 1 = $1+$**  
  All alkali metals--group 1--have an oxidation number of +1.

* **Group 2 = $2+$**  
  All alkaline earths--group 2--have an oxidation number of +2.

* **$\textrm{F}$ = $1-$**  
  Fluorine is the most electronegative element, so its oxidation number is always -1.

* **$\textrm{H}^+$ = $1+$, or $\textrm{H}^-$ = $1-$**  
  Hydrogen has an oxidation number of +1 in most cases.  
  In an ionic ~~hydride~~, hydrogen has an oxidation number of -1.  
  *e.g. $\textrm{NaH}$ aka. $\textrm{Na}^+\textrm{H}^-$*

* **$\textrm{O}$ = $2-$, or $\textrm{O}$ = $1-$**  
  Oxygen has an oxidation number of -2 in most cases.  
  In a peroxide, which is $\textrm{O}_2^{2-}$, oxygen has an oxidation number of -1.  
  *e.g. $\textrm{H}_2\textrm{O}_2$, $\textrm{Na}_2\textrm{O}_2$*

## Examples
The oxidation number of an element is typically written above it. I cannot do that, so it'll be beside, the elements the same order as in the compound.

[Oxidation Number Calculator](https://www.periodni.com/oxidation_numbers_calculator.php)

* $\textrm{S}_8$: 0
* $\textrm{H}_2\textrm{S}$: 1+, 2+
* $\textrm{CuF}_2$: 2+, 1-
* $\textrm{PbCrO}_4$: 2+, 6+, 2-
* $(\textrm{Cr}_2\textrm{O}_7)^{2-}$: 6+, 2-

* Probably won't appear on exams: $\textrm{I}_3^-$: -1/3



# Spontaneity
You can determine if a redox reaction will be spontaneous or not using the reduction half reactions on ~~page 7~~.

![Page 7](images/p7.jpg)

## Interpretation
The left hand side contains oxidizing agents. (meaning they reduce) 
The right hand side contains reduction agents. (meaning they oxidize)

The strength of the oxidizing agents increases as you go up in the page.  
The strength of the decreases agents increases as you go down in the page.  

To put it short, ~~top left is strongest oxidizing agent~~, ~~bottom right is strongest reducing agent~~.

## Application
A spontaneous redox reaction only occurs if the ~~oxidizing agent is stronger/above the reducing agent~~ in the table.  

<span id="ib">IB</span> *Since the only point of IB is mindless memorization, their data booklet's table is upside-down.*  
For ~~only the IB table~~, a spontaneous redox reaction only occurs if the ~~reducing agent is above the oxidizing agent~~ in the table.  
