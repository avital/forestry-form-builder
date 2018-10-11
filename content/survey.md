+++
date = "2018-06-20T19:02:14+00:00"
draft = true
recipient = "survey-answers@example.com"
submit_text = ""
title = "Survey"
[form]
recipient = "depthfirstlearning@gmail.com"
submit_text = "Apply for the DFL fellowship"
type = "long"
[[form.sections]]
title = "Tell us about yourself"
[[form.sections.fields]]
description = "For example, degrees, other training, public projects, publications, talks"
label = "Tell us about your background in Machine Learning"
name = "about_you"
template = "textarea"
type = "textarea"
[[form.sections.fields]]
description = "For example, papers to lead to, or fundamental topics to cover."
label = "What topics would you want to plan DFL classes on?"
name = "topics"
template = "textarea"
type = "textarea"
[[form.sections]]
title = "Commitment"
[[form.sections.fields]]
label = "How much weekly time can you spend on this?"
name = "time"
template = "text-field"
type = "text"
[[form.sections.fields]]
label = "Would you like to share the responsibility for planning the class with someone else?"
name = "share"
template = "checkbox"
type = "checkbox"
[[form.sections.fields]]
description = "Name and a bit about the person."
label = "If so, with who?"
name = "with_who"
template = "text-field"
type = "text"

+++
