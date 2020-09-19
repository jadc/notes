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

You can determine these by...
* Checking if charges change from the resultant to product side.
* Checking if oxidation numbers (covered later) change from the resultant to product side.
* Checking if the ion is anywhere on the half reduction reaction table. (covered later)

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
* $\textrm{NH}_4\textrm{NO}_3$: -3, +1, +5, -2
  * This is unique, because its actually two polyatomic ions combined together.  
    $\textrm{NH}_4$ has a 1+ charge, and $\textrm{NO}_3$ has a 1- charge.

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

In addition, the ~~greater the distance~~ between the two agents, the ~~faster the reaction~~ will occur.

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

You can then write a reduction half reaction table, strongest oxidizing agent in the top left, strongest reducing agent in the bottom right.

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
2. ~~Add $\textrm{H}_2\textrm{O}_{\textrm{(l)}}$~~.

#### Strong Acids
If the species is a strong acid...
1. ~~Ionize~~/separate the acid into its ions. (the acid's anion & ~~$\textrm{H}^+_{\textrm{(aq)}}$~~)
2. ~~Add $\textrm{H}_2\textrm{O}_{\textrm{(l)}}$~~.

**Example**  
$\textrm{HCl}_{\textrm{(aq)}}$'s components are...
* $\textrm{Cl}^-_{\textrm{(aq)}}$.
* $\textrm{H}^+_{\textrm{(aq)}}$.

### Extra Tips
* If the question mentions...
  * just an elements name and nothing else, such as "Copper is added..."  
    It is most likely a solid copper atom with no charge.
  * "exposed to moist air."  
    It most likely just means water and air is present.
* Most *(not all!)* oxides have low solubility. (e.g. $\textrm{PbO}_2$)

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

5. Balance the ~~net charges of the entire sides~~ by adding electrons like before.

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

## More Examples
![](images/balance2.jpg)
![](images/balance3.jpg)



# Disproportionation
*also known as Autoxidation.*  
For the 30 level, all you need to do is be ~~**be able to identify them**~~ in an equation. No balancing needed.

When a single species is *both* oxidized and reduced.  
Atoms within a molecule or polyatomic ion increase in oxidation number. (reduce)
Atoms outside a molecule or polyatomic ion, but ~~of the same element~~, decrease in oxidation number. (oxidize)

## Steps
1. Identify the oxidation numbers of all atoms in the equation.
2. Determine if any element on one side has two of the same element on the other with different oxidation numbers.  
   If so, disproportionation has occured.

#### Examples
$\textrm{H}_2\textrm{O}_2 \longleftrightarrow \textrm{H}_2\textrm{O} + \textrm{O}_2$

**Oxidation #s**
* $\textrm{H}_2$: +1
* $\textrm{O}_2$: -1

$\longleftrightarrow$

* $\textrm{H}_2$: +1
* $\textrm{O}$: -2
* $\textrm{O}_2$: 0

As you can see, the -1 charged oxygen ends up as both -2 (reduction) and 0 (oxidation).  
Therefore, since it did both, this is disproportionation.



# Electrochemical Cells

**Electrochemical Processes**  
The conversion of chemical energy into electrical energy (voltaic),  
and the conversion of electrical energy into chemical energy (electrolytic).  
These are redox reactions.

## Voltaic Cells
Voltaic cells are electrochemical cells that convert chemical energy into electrical energy.

It is usually a ~~metal rod~~ submerged in a ~~solution of one of its ions~~.

#### Half Cells
One part of a voltaic cell.  
Either oxidation or reduction occurs.

#### Porous Partition
The two half cells are separated by a porous partition.  

This can either be a...
* salt bridge (solution containing a conducting solution)
* porous cup

The purpose of the partition is to allow the passage of ions/electrons without the solutions mixing completely.

![](images/cells.png)

#### Electrolyte
The conducting solution.  
Usually is comprised of the ~~same ions as the electrode~~ in said solution.

The positive electrolyte---the one that the cathode is submerged in---is called the anolyte.  
The negative electrolyte---the one that the anode is submerged in---is called the catholyte.

#### Redox Couple
The reduced and oxidized forms of a chemical entity.  
In other words, the pair of chemical entities in a half reaction.  
*e.g. $\textrm{Cu}_{\textrm{(s)}}$ and $\textrm{Cu}^{2+}_{\textrm{(aq)}}$ are a redox couple.*

## Electrodes
A conductor in a circuit.  
Carries electrons to or from a substances.

#### Anode
The electrode where ~~oxidation~~ occurs. (therefore, its the reducing agent)  
Electrons are given off/lost here. # of electrons decreases.  
It is the ~~negative electrode~~.

~~Corrosion occurs at the anode.~~

#### Cathode
The electrode where ~~reduction~~ occurs. (therefore, its the oxidizing agent)  
Electrons are recieved/gained here. # of electrons increases.  
It is the ~~positive electrode~~.

~~Solid formation occurs at the cathode.~~

#### Direction
The direction that electrons flow is ~~**always from anode to cathode**~~.  
You can remember this by the saying, *"the cat goes home."* Cat-hode, cat-home. Get it? ![4HEad](https://cdn.frankerfacez.com/emoticon/128247/1)

## Anions and Cations
Anions and cations are also being transferred from anode to cathode. However...
* ~~Excess cations at the anode~~ migrate through the salt bridge ~~to the cathode~~.
* ~~Excess anions at the cathode~~ migrate through the salt bridge ~~to the anion~~.

## Standard Voltaic Cells
* $25^\circ\textrm{C}$.
* Electrolyte at $1.0 \textrm{ mol}\cdot\textrm{dm}^{-3} (aka. \frac{\textrm{mol}}{\textrm{L}})$ concentratiion.
* Comprises of two standard half cells/electrodes.
  * Must contain a solid electrode. Usually one of the entities in the redox couple.
* Contains a redox couple.

![half cells](images/halfcells.png)

## No Solid Electrode
If a half cell has a solution of an ion, the electrode has to be the solid variant of that entity.  
Sometimes this isn't possible---as in, the ion has no solid (usually metallic) variant---such as with $\textrm{MnO}^-_{\textrm{4 (aq)}}$ or $\textrm{Cr}_2\textrm{O}^{2-}_{\textrm{7 (aq)}}$.

You still need a solid electrode, so an ~~inert electrode~~ must be selected, so that it does not partake in the electrochemistry.  
There are two options.

### Carbon
Cheap, but not completely inert.
(~~No good when oxygen is a product~~)

![](images/carbon.png)

### Platinum
Expensive, but completely inert.

![](images/platinum.png)

## Gas Electrode Required
If one of the components of a redox couple is a gas, such as in a hydrogen electrode.

A platinum electrode is dipped into the electrolyte.  
The gas flows over it at standard pressure.

![](images/hydrogen-electrode.png)

In this example, platinum is the *inert* electrode, H<sup>+</sup> is the electrolyte, and hydrogen gas is the electrode that actually reacts.

## Cell Notation
```
anode / anolyte // catholyte / canode
```

The double slash (//) is a symbol for the bridge between the half cells. (salt bridge or porous cup)

*e.g. for a copper and zinc couple*  
$\textrm{Cu}_{\textrm{(s)}} / \textrm{Cu}^{2+}_{\textrm{(aq)}} // \textrm{Zn}^+{2+}_{\textrm{(aq)}} / \textrm{Zn}_{\textrm{(s)}}$

### "Multiple" Anolytes
If there is more than just an anode and anolyte, write every compound except the anode as the anolyte.

#### Example
The cell notation for each half cell is written below it.

![](images/multiple.png)

# Electric Potential
Measured in volts, $\textrm{V}$, the ability of the cell to produce an electric current.  
It is the competition between the two half cells for electrons.

## Potential
The potential of an isolated half cell cannot be measured. Two half cells together produce an electric current.

#### Reduction
The higher the electric potential, the more likely the cell will reduce, gaining electrons.  
This is the reduction potential, $\textrm{E}^0_{\textrm{red}}$.

#### Oxidation
The lower the electric potential, the more likely the cell will oxidize, losing electrons.  
This is the oxidation potential, $\textrm{E}^0_{\textrm{oxid}}$.

## The 0
The "<sup>0</sup>" on the E means the cell potential was measured when...
* ion concentration of the half cells are $1.00 \frac{\textrm{mol}}{\textrm{L}}$
* conditions are STP

## Predicting
The *reduction* potential of all cells is listed on the right-most column on page 7.  

### Method 1
Subtract the reduction potential of the anode from the reduction potential of the cathode.

$\textrm{E}^0_{\textrm{net}} = \textrm{E}^0_{\textrm{red cathode}} - \textrm{E}^0_{\textrm{red anode}}$

### Method 2
This is the harder for no reason method. Only here to give more information.  
The sum of the reduction and oxidation potential. The oxidation potential is the opposite sign as the reduction potential.

$\textrm{E}^0_{\textrm{oxid}} = -\textrm{E}^0_{\textrm{red}}$

$\textrm{E}^0_{\textrm{net}} = \textrm{E}^0_{\textrm{red}} + \textrm{E}^0_{\textrm{oxid}}$

## Application
A voltmeter or multimeter will measure the ~~electric potential difference~~ of two half cells.

## Reference Electrode
Absolute numbers cannot be measured---only their differences---therefore a reference electrode is used.

In standard scenarios, this electrode is **hydrogen**.  
Hydrogen is given a value of $0.00 \textrm{V}$. This does not mean it has no electric potential, its just relative to hydrogen.

A standard hydrogen electrode is a platinum electrode immersed in a solution of hydrogen ions at a concentration of $1.00 \frac{\textrm{mol}}{\textrm{L}}$. H<sub>2</sub> gas is bubbled around the inert electrode. The half reaction that occurs is...

$2\textrm{H}^+_{\textrm{(aq)}} + 2e^- \longleftrightarrow \textrm{H}_{2 \textrm{(g)}}$  
$\textrm{E}^0_{\textrm{H}^+} = 0.00 \textrm{V}$

### Different Reference Electrode
You can choose any reduction half reaction's electric potential from page 7 as the reference electrode.  
Electric potential difference is unaffected by doing this.

#### Steps
1. Add/subtract to make your desired reference electrode's electric potential equal 0.
2. Perform this same arithmetic to every electric potential on the table.
Now all the electric potentials are relative to your new reference electrode.

## Spontenity
A ~~positive~~ electric potential difference means the reaction is ~~spontaneous~~.

# Completing A Cell
Some questions will ask you to complete a cell. This includes...
* [label all components](#label-all-components)
* [cell notation](#cell-notation)
* [half reactions](#half-reactions)
* net redox reaction (just add the half reactions together)
* E<sup>0</sup> of each half cell (read right-most column of page 7)
* [E<sup>0</sup> of net reaction](#electric-potential)
* [evidence](#evidence)

Click these links to see what you have to do.

The finished question should look like this.
![](images/complete.png)

## Label All Components
* Identify and label the SOA and the SRA between the half cells.  
  The half cell with the SOA should be labeled as the ~~cathode~~.  
  The half cell with the SRA should be labeled as the ~~anode~~.

* Identify and label any inert electrodes. (platinum and carbon)

* Draw the voltmeter.
  * Draw a line connecting the electrodes of each half cell.
  * Make sure both lines connect to a voltmeter, denoted by a V in a circle.
  * Draw arrows indicating the flow of electrons. (anode to cathode)

* Draw the salt bridge. (you could draw porous cups---a salt bridge is easier to draw)
  * State what the salt bridge is made of.  
    It must not partake in the electrochemistry, so $\textrm{KNO}_{3 \textrm{ (s)}}$ is often used, since its composed of spectator ions.

* Draw the pathway of anions and cations.
  * An arrow from the salt bridge and from the solution pointing towards the relevant electrode.  
    *for instance, anions come from the salt bridge and anolyte and go into the anode*

## Evidence
You must write a brief sentence describing the qualitative evidence of electrons being transferred.

### Electric Potential
If the E<sup>0</sup><sub>net</sub> that you calculated earlier is positive, this is evidence of electrons being transferred.

### pH
If there are ~~more H<sup>+</sup>~~ ions on the product side of the net reaction compared to the reactant side, then the reaction became ~~more acidic~~.  
If there are ~~less H<sup>+</sup>~~ ions on the product side of the net reaction compared to the reactant side, then the reaction became ~~more basic~~.

You can state this by saying red/blue litmus paper turns blue/red, depending on basic/acidic respectively.

### Solid Products
In a redox couple, if the ~~ion reactant becomes a solid product~~, that means the ~~solid is forming on the cathode~~. (since its always anode to cathode)  
In a redox couple, if the ~~product reactant becomes an ion product~~, that means the ~~anode is being corroded~~. (since its always anode to cathode)

#### Example
$\textrm{Cu}^{2+}_{\textrm{(aq)}} + \textrm{Zn}_{\textrm{(s)}} \longleftrightarrow \textrm{Cu}_{\textrm{(s)}} + \textrm{Zn}^{2+}_{\textrm{(aq)}}$

* Solid zinc anode corrodes.
* Solid copper forms at cathode.

If you are wondering *why* copper forms at the cathode, its because both electrons and cations (Cu<sup>2+</sup><sub>(aq)</sub>) are being transferred to the cathode. This is the recipe to forming copper atoms.



# Batteries
A battery contains two or more cells linked together for a ~~combined higher voltage~~.

You don't have to memorize the real life examples, and more detail is in the actual booklet.


## Primary Cells
* ~~Not rechargeable~~.
  * Products/by-products are either too delicate or unsuitable for recharging.
* Deliever a ~~constant voltage~~ over their entire lifetime.

#### Examples
* LeClanche Cell
  * old acid battery
  * 1.5 V
* Alkaline Dry Cell
  * modern battery
  * 1.5 V
* Mercury Cell
  * disc shaped small battery
  * 1.35 V

## Secondary Cells
* ~~Rechargeable~~.
  * Uses electricity to ~~reverse the redox reaction~~ that usually produces electricity.

#### Examples
* Lithium-Ion Battery
  * modern phone battery
  * anode is lithium, cathode is TiS<sub>2</sub>
  * 3 V
* Nickel-Cadmium Cell
  * cheapest rechargeable
  * looks like LeClanche Cell
  * has a memory effect
    * over time, the cell will "think" its minimum is the lowest charge its had.
    * if this isn't 0%, then you'll have less capacity.
  * 1.25 V
* Lead Storage Battery (Car Battery)
  * two lead electrodes submerged in sulphuric acid
  * acid thickens in cold, battery stops working; not dead, just need to warm up
  * 12 V

## Fuel Cells
* ~~Do not need to be recharged~~.
* Requires a ~~constant supply of fuel~~.
  * emphasis on constant: it cannot store energy, electricity will cease if fuel supply does
* ~~Electrical energy~~ obtained from ~~fuel oxidizing~~.

#### Examples
* Hydrogen Fuel Cell
  * input is hydrogen and oxygen gas.
  * output is water.
  * more efficient than combustion engines, less lost to heat. (40% vs 80%)

* Aluminum-Air Cell
  * fuel is solid aluminum and oxygen gas.

# Corrosion
The deterioration of metals by electrochemical means.  
*e.g. iron rusting, silver tarnishing, copper patina*

#### Rust
In rusting, ~~oxygen and water~~ act as ~~oxidizing agents~~, and oxidize metals.

$\textrm{O}_{2 \textrm{(s)}} + 2\textrm{H}_2\textrm{O}_{\textrm{(l)}} + 4e^- \longleftrightarrow 4\textrm{OH}^-_{\textrm{(aq)}}$  
$E^0_{\textrm{red}} = +0.40 \textrm{ V}$

In acidic conditions...  
$\textrm{O}_{2 \textrm{(g)}} + 4\textrm{H}^+_{\textrm{(aq)}} + 4e^- \longleftrightarrow 2\textrm{H}_2\textrm{O}_{\textrm{(l)}}$  
$E^0_{\textrm{red}} = +1.23 \textrm{ V}$

## Prevention
* **Painting**
* **Oiling/greasing**
* **Plasticizing**
  * plastic used for the inner surface of food cans
* **Dipping**
  * dip iron into another metal that forms a non-porous oxide
  * magnesium and zinc are used sincen they are oxidized over iron
* **Galvanizing/electroplating**
  * electrolytic process
  * adds thin layer of metals (above iron in page 7)
* **Alloying**
  * some alloys form a thin layer that prevents oxidation/corrosion
  * e.g. stainless steel. iron + chromium + nickel. forms a thin layer of chromium oxide
* **Sacrificial Anode**
  * main metal corrodes and loses electrons
  * however, the lost electrons are immediately replenished by a sacrificial anode connected to it
  * in the end, the anode corrodes instead
  * anode typically composed of zinc or magnesium
* **Cathodic Protection**
  * connect the corrosive metal to the negative of a DC electrical circuit
  * metal flooded with electrons, discouraging oxidation
  * e.g. bodywork of cars connected to negative of car battery
