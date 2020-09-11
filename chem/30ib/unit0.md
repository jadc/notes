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
$\textrm{Mg} \longleftrightarrow \textrm{Mg}^{2+} + 2e^-$

~~$e^-$ always on the **right** of the arrow.~~

##### Reduction Half Reaction Example
$\textrm{S} + 2e^- \longleftrightarrow \textrm{S}^{2-}$

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
      *e.g. $\textrm{Br}_2 + 2e^- \longleftrightarrow 2\textrm{Br}^-$, $2\textrm{Br}^-$ needs 2 electrons to be neutral.*
3. Write out the equation showing ions.  
   This can be done by ~~cancelling the equal electrons~~ between both half reactions.
4. Verify that the sum of charges of all ions on both sides remains constant. (if not, it isn't truly redox)

#### Example Problem
*What is oxidized and what is reduced in the following reaction?*

$2\textrm{AgNO}_3 + \textrm{Cu} \longleftrightarrow \textrm{Cu} ( \textrm{NO}_3 )_2 + 2\textrm{Ag}$

1. $\textrm{NO}_3^-$ is a spectator ion. Ignore it.  

2. $2\textrm{Ag}^+ + 2e^- \longleftrightarrow 2\textrm{Ag}$ (or $2(\textrm{Ag}^+ + e^- \longleftrightarrow \textrm{Ag})$)  
   *($\textrm{Ag}$ went from missing 1 electron to being balanced, but since there are 2 of them on both sides, 2 electrons were actually missing)*

   $\textrm{Cu} \longleftrightarrow \textrm{Cu}^{2+} + 2e^-$

3. $2\textrm{Ag}^+ + \textrm{Cu} \longleftrightarrow 2\textrm{Ag} + \textrm{Cu}^{2+}$

4.

The following tables are simply the charges of each ion in the equation.

| $2\textrm{Ag}^+$ | $+$ | $\textrm{Cu}$ | $\longleftrightarrow$ | $2\textrm{Ag}$ | $+$ | $\textrm{Cu}^{2+}$ |
| --- | --- | --- | --- | --- | --- | --- |
| $2+$ | $+$ | $0$ | $=$ | $0$ | $+$ | $2+$ |

They are equal on both sides, therefore the redox reaction is verified.

## Inequal Net Charges
Sometimes the net charges of both sides of the equation will not be equal, despite being a redox reaction.

In these cases, multiply both half reactions by whatever you need to so that the net electrons of both half reactions are equal.

#### Example Problem
$\textrm{Al} + \textrm{Cd}(\textrm{NO}_3)_2 \longleftrightarrow \textrm{Al}(\textrm{NO}_3)_3 + \textrm{Cd}$

1. $\textrm{NO}_3^-$ is a spectator ion. Ignore it.  

2. $\textrm{Al} \longleftrightarrow \textrm{Al}^{3+} + 3e^-$  
   $\textrm{Cd}^{2+} + 2e^- \longleftrightarrow \textrm{Cd}$

   Issue: The electrons of both equations do not cancel with each other.  
   Solution: Multiply each entire half reaction by something so that the electrons are equal and can cancel.

   $2(\textrm{Al} \longleftrightarrow \textrm{Al}^{3+} + 3e^-)$  
   $3(\textrm{Cd}^{2+} + 2e^- \longleftrightarrow \textrm{Cd})$

   $2\textrm{Al} \longleftrightarrow 2\textrm{Al}^{3+} + 6e^-$  
   $3\textrm{Cd}^{2+} + 6e^- \longleftrightarrow 3\textrm{Cd}$

   Now both half reactions have $6e^-$.

3. $2\textrm{Al} + 3\textrm{Cd}^{2+} \longleftrightarrow 2\textrm{Al}^{3+} + 3\textrm{Cd}$  
   Net charge is constant: $0 + +6 = +6 + 0$

## Don't Be Fooled By Compounds
Always separate compounds before determining if there was an electron transfer.

#### Example Problem
$\textrm{Pb}^{2+} + 2\textrm{I}^- \longleftrightarrow \textrm{PbI}_2$

Seems like electrons were transferred, but separate the elements in the compound...

$\textrm{Pb}^{2+} + 2\textrm{I}^- \longleftrightarrow \textrm{Pb}^{2+} + 2\textrm{I}^-$

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



# Making Reduction Half Reaction Tables

## From Lab Data
There are often problems that feature a table, with oxidizing agents at the top, and reducing agents on the sides.

![lab data](images/fromlabdata.jpg)

The blue dots denote that the reaction was spontaneous.

The element that is spontaneous with more other elements is the stronger oxidizing agent and weaker reducing agent.  
The element that is spontaneous with fewer other elements is the weaker oxidizing agent and stronger reducing agent.

You can then write a reduction half reaction table, strongest oxidizing agent in the top left, strongest reducing agent in the bottom left.

## From Reactions
The following steps are to be used when asked for a reduction half reaction table.  
You will usually be given a series of redox reactions...
* some with a solution
* some with "no evidence of reaction," meaning there was no reaction.

## Steps
1. Identify the oxidation agent and the reduction agent.  
   *(remember, OA reduces/gains $e^-$, RA oxidizes/loses $e^-$)*

2. If there is evidence of a reaction, the reaction is spontaneous, so the OA must be above the RA in the table.  
   You can denote this with $\dfrac{\textrm{OA}}{\textrm{RA}}$ (charges not needed)

   If there is no evidence of a reaction, the reaction is non-spontaneous, so the RA must be above the OA in the table.  
   You can denote this with $\dfrac{\textrm{RA}}{\textrm{OA}}$ (charges not needed)

   Do this for every unique element in the reaction.

3. Combine the denotations to get the order of the table.  
   *e.g. If I had $\dfrac{\textrm{X}}{\textrm{Y}}$ and $\dfrac{\textrm{Y}}{\textrm{Z}}$, then the combined true order is X/Y/Z.*

3. Once you have the order, write a redox reaction for each unique element in said order.  
   $\textrm{OA}^x + xe^- \longleftrightarrow \textrm{OA}$  
   $x$: the charge of the OA from anywhere, even across equations in the same problem.  

4. With a complete "table"/list, you can now determine...  
   * The highest element on the left-hand side (top-left) is the ~~strongest oxidation agent~~. (SOA)
   * The lowest element on the right-hand side (bottom-right) is the ~~strongest reduction agent~~. (SRA)

#### Example
![from reactions](images/fromreactions.jpg)

In this example...
* $\textrm{Co}^{2+}$ is the strongest oxidizing agent
* $\textrm{Mg}$ is the strongest reducing agent
* $\textrm{Mg}^{2+}$ is the weakest oxidizing agent
* $\textrm{Co}$ is the weakest reducing agent



# Predicting Redox Reactions
When given a mixture of aqueous substances (ions and molecules), you may be asked to predict which substances will react.  
This heavily relies on page 7 of your data booklet.

## Identifying Substances
For reaction prediction questions, most of the time you will be given a *word problem*, and you have to find out the equation notation for each one.  
Here are some tips.

### Atoms
If the species is an atom, include it with ~~no modifications~~.  
Make sure to properly denote diatomic and polyatomic atoms from Science 10. (e.g. $S_8$)

### Molecular
If the species is molecular compound, include it with ~~no modifications~~.

### Ionic
For ionic species, you need to check the solubility of the compound using page 6 in your data booklet.

#### Low Solubility
If the species is a lowly soluble ionic compound, include it with ~~no modifications~~.

#### High Solubility
If the species is a highly soluble ionic compound...
1. ~~Dissociate~~/separate the compound into its ions.
2. ~~Add $\textrm{H}_2\textrm{O}_{\textrm{(l)}}$~~ to the equation.

### Acids
For acid species, you need to check if the acid is strong or weak.  
An acid is strong if it is one of the first six in the table on page 8 in your data booklet.  
Otherwise, its weak.

#### Weak Acids
If the species is a weak acid...
1. Include it with ~~no modifications~~.
2. ~~Add $\textrm{H}_2\textrm{O}_{\textrm{(l)}}$~~ to the equation.

#### Strong Acids
If the species is a strong acid...
1. ~~Ionize~~/separate the acid into its ions.
2. ~~Add $\textrm{H}^+_{\textrm{(aq)}}$ and $\textrm{H}_2\textrm{O}_{\textrm{(l)}}$~~ to the equation.

### Extra Tips
* If the question mentions...
  * just an elements name and nothing else, such as "Copper is added..."  
    It is most likely a solid copper atom with no charge.
  * "exposed to moist air."  
    It most likely just means water is present.
* *Most* (not all!) oxides have low solubility. (e.g. $\textrm{PbO}_2$)

## Steps
1. * For every substance identified (see previous section), find out whether they are an oxidizing agent or a reducing agent, using page 7 and seeing if they are on the left or right side respectively.
   * Some substances can appear on both sides on the table, meaning they are both an oxidizing and reducing agent. Make sure not to mix up their reactions.
   * Some substances are not agents on their own, rather only when other specific substances are present. Make sure to include these, making it clear that they are only an agent when together.

2. The predicted redox reactions will only occur with the strongest oxidizing agent and the strongest reduction agent.  
   Identify both of those as usual. (strongest oxidizing top left of table, strongest reducing bottom right of table)

3. Once each strongest agent is identified, write down the entire equation/line of both.
   * Make sure one reaction is reduction and one reaction is oxidation.  
     (one with electrons before arrow, one with electrons after)  
     You can switch between the two if needed by swapping the substances on each side. (i.e. write it backwards)

Beyond this point is things you've done before.

4. Get the electrons on both sides to equal the same to cancel them. You can do this by multiplying by the lowest common denominator.

5. Combine the reactions after cancelling the electrons.

6. As long as the oxidizing agent is still above the reducing agent in the table, you can also state that the equation is spontaneous.  
   (no specific way to do this, I personally just write an 'S' above the arrow)

#### Example
![predicting](images/predict.jpg)



# Balancing Redox Equations
Ultimately you still end up with a net redox reaction, but these questions give you an unbalanced redox equation.  
You need to balance said equations without using page 7.

## Steps (Half Reaction Method)
1. Break down the redox reaction into half reactions. You should have two (unfinished) half reactions.
   * Pair up each compound on one side with the other.  
     Make sure to pair up compounds that share an element.

For each of the two half reactions, perform the following steps.

2. Use coefficients to balance the quantity of atoms on both sides, **except oxygen and hydrogen**.

3. Add any number of $\textrm{H}_2\textrm{O}_{\textrm{(l)}}$ molecules to balance the quantity of oxygen on both sides.

4. Add any number of $\textrm{H}^+_{\textrm{(aq)}}$ molecules on the other side of the water molcules to balance the quantity of hydrogen on both sides.  
   *(you are essentially undoing the hydrogens you added with water)*

*(For 3. and 4., make sure to account for pre-existing quantities of H & O)*

5. Balance the charges by adding electrons like before.

Everything beyond this point is not new.

6. If the electrons in both half equations are equal, cancel them out.  
   If not, multiply both half equations by a lowest common denominator to make them equal.

7. Combine the half reactions. Reduce coefficients of substances on both sides if possible.

8. Verify that it's still a redox reaction by making sure net charges on both sides are equal, like before.

### Summary
1. Split into 1/2 Reactions
Then, balance...
2. Atoms (no O or H)
3. Oxygens
4. Hydrogens
5. Charges (aka. Cancel Electrons)

## Example
### Step-by-Step
$\textrm{NO}_3^- + \textrm{P}_4 \longleftrightarrow \textrm{H}_3\textrm{PO}_4 + \textrm{NO}_2$

1. Reduction  
   OA ---> $\textrm{NO}_3^- \longleftrightarrow \textrm{NO}_2$  
   Oxidation  
   RA ---> $\textrm{P}_4 \longleftrightarrow \textrm{H}_3\textrm{PO}_4$

2. $\textrm{NO}_3^- \longleftrightarrow \textrm{NO}_2$  
   $\textrm{P}_4 \longleftrightarrow 4\textrm{H}_3\textrm{PO}_4$

3. $\textrm{NO}_3^- \longleftrightarrow \textrm{NO}_2 + \textrm{H}_2\textrm{O}$  
   $16\textrm{H}_2\textrm{O} + \textrm{P}_4 \longleftrightarrow 4\textrm{H}_3\textrm{PO}_4$

4. $2\textrm{H}^+ + \textrm{NO}_3^- \longleftrightarrow \textrm{NO}_2 + \textrm{H}_2\textrm{O}$  
   $16\textrm{H}_2\textrm{O} + \textrm{P}_4 \longleftrightarrow 4\textrm{H}_3\textrm{PO}_4 + 20\textrm{H}^+$

5. $1e^- + 2\textrm{H}^+ + \textrm{NO}_3^- \longleftrightarrow \textrm{NO}_2 + \textrm{H}_2\textrm{O}$  
   $16\textrm{H}_2\textrm{O} + \textrm{P}_4 \longleftrightarrow 4\textrm{H}_3\textrm{PO}_4 + 20\textrm{H}^+ + 20e^-$

6. $20(1e^- + 2\textrm{H}^+ + \textrm{NO}_3^- \longleftrightarrow \textrm{NO}_2 + \textrm{H}_2\textrm{O})$  
   $16\textrm{H}_2\textrm{O} + \textrm{P}_4 \longleftrightarrow 4\textrm{H}_3\textrm{PO}_4 + 20\textrm{H}^+ + 20e^-$

7. $40\textrm{H}^+ + 20\textrm{NO}_3^- + 16\textrm{H}_2\textrm{O} + \textrm{P}_4 \longleftrightarrow 20\textrm{NO}_2 + 20\textrm{H}_2\textrm{O} + 4\textrm{H}_3\textrm{PO}_4 + 20\textrm{H}^+$

  Simplified:  
  $20\textrm{H}^+ + 20\textrm{NO}_3^- + \textrm{P}_4 \longleftrightarrow 20\textrm{NO}_2 + 4\textrm{H}_2\textrm{O} + 4\textrm{H}_3\textrm{PO}_4$

8. $+20$ + $-20$ + $0$ = $0$ + $0$ + $0$

### Concise
![balancing](images/balance.jpg)
