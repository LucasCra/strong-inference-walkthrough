# Strong inference, one step at a time

An interactive walkthrough of a research workflow built on Platt's strong inference, with Chamberlin's multiple working hypotheses, Fudge's front end and Popper's rules. It plays two invented ML projects through the cycle and shows what each step needs, does, outputs and stores, and how the notebook of knowledge grows.

**Status: a concept with one real run behind it.** A harness built from an earlier draft of this workflow ran once on a real problem (the Kaggle competition *Name That LLM*, 2026-10-31 to 11-01). Three mechanisms were added from what that run showed: a loop record of how the estimates have fared, the cause of each missed prediction, and a gate that parks a branch whose rivals grow faster than they close. Every run and number in the walkthrough is still invented, except two facts marked (real).

A second page, [index.html#kaggle](index.html#kaggle), shows how a Kaggle competition drives the same cycle: a ledger of levers outside, strong inference on puzzles inside, calibration of the local measurement against the public board per training regime, and blocked levers that wait for the person. It walks an invented competition shaped like *Name That LLM*. It is a first version, untested as a whole.

The site is a single file, [index.html](index.html), with both pages. It needs internet only for its fonts. The diagrams are [strong_inference_workflow.drawio](strong_inference_workflow.drawio) (the base cycle) and [strong_inference_kaggle_workflow.drawio](strong_inference_kaggle_workflow.drawio) (the Kaggle adaptation).
