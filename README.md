### Hi there 👋

 fact: ...
-->
import { Solomon, Bio } from "portfolio"

class AboutMe extends Solomon.Bio {
  const getDailyKnowledge = () => {
    return (
		[
		    id: 1, name: 'HTML',
		    id: 2, name: 'CSS',
		    id: 3, name: 'Javascript',
		    id: 4, name: 'REACT'
		 ]
	   )
     }

    render (
      return (
	 <div>
	    {getDailyKnowledge().map(item => {
		return(
		  {item.id} {item.name}
		)
	    })}
	 </div>
	)
    )
}

export default AboutMe
