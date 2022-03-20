<template>
  <div class="about">
    <h1>Weather in Kosovo</h1>
   
 <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime, earum.</p>
 <a @click="readmore=!readmore">{{linktitle}}</a>
<transition name="fade">

 <div v-if="readmore">
   <p>
     Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias nobis porro rerum illum veritatis quasi dolore nemo, numquam, culpa inventore placeat sunt optio facilis excepturi in temporibus, eligendi maxime iure officiis incidunt dolores iste. Nesciunt libero dolorem voluptate id, necessitatibus blanditiis! Necessitatibus nihil autem sapiente? Laborum, maxime minima provident fuga ut nesciunt magnam atque dolor odio, facere et cum rem sit error, perspiciatis velit corporis ab doloribus inventore eaque veniam deserunt ipsa maiores. Corrupti ut suscipit iusto. Odit aut suscipit unde omnis sunt eveniet quasi inventore, dolorem earum, facilis eligendi pariatur eius necessitatibus voluptate, doloremque fugiat commodi ad repellat et. Assumenda debitis iure non deleniti reprehenderit, voluptatum dolores sint alias nam mollitia et minima quos, excepturi provident vitae molestias sunt. Ea voluptatibus dignissimos magnam nihil, vel possimus voluptatem aut dolorem aliquam? Voluptate sint corrupti, cumque quaerat obcaecati officia ipsam nobis voluptatem velit fuga beatae. Tenetur quis omnis officia rem eligendi. Vel iste, voluptate corrupti cupiditate explicabo officia debitis, dolorem nihil praesentium ullam enim amet, quo deserunt. Nesciunt, blanditiis! Vel commodi illum, itaque repudiandae voluptas labore pariatur delectus id necessitatibus possimus magnam dicta iste nisi. Rem perferendis consequatur id veritatis temporibus debitis natus. Earum libero id molestiae esse suscipit architecto commodi voluptas sequi voluptate, excepturi neque blanditiis iure voluptatum quasi porro eum fugit sunt recusandae culpa nisi modi adipisci. Aut repellat minus qui cumque quidem modi voluptatibus deleniti quasi. Praesentium doloribus suscipit dignissimos distinctio neque corrupti ea autem necessitatibus fugit nisi in nihil excepturi rem rerum veniam, soluta similique magnam omnis sed, laudantium sequi. Officia non eaque delectus ipsam nulla veritatis iusto doloremque fugiat enim suscipit incidunt similique atque tempora blanditiis corporis, cupiditate molestias explicabo. A incidunt ut illo voluptate ratione recusandae earum inventore autem! Soluta ad ea ipsam quidem impedit perspiciatis esse sed unde exercitationem ut sunt facere dignissimos, illum error architecto adipisci aspernatur voluptates assumenda, amet, aliquid quis vitae nihil recusandae! Quo a excepturi dolorum fuga recusandae tenetur ea esse, earum ipsam? Consequatur cum quia veritatis vitae corrupti, velit iusto, reiciendis aliquam magnam, necessitatibus unde nostrum suscipit rerum facere nihil itaque alias optio recusandae eius laudantium aut repellat perspiciatis impedit sunt! Placeat neque excepturi dolorum eius voluptatem magnam dolores. Ad alias nostrum eos blanditiis ut quas hic aut rerum reprehenderit ex? Rerum nulla quae, vero recusandae vel quia amet quis quibusdam iure dolorem deleniti soluta ratione labore reprehenderit impedit est nostrum, illum dolores. Aut commodi id saepe nemo ea voluptate laborum obcaecati! Corrupti quia repellendus dicta, illum rem voluptate reiciendis ab commodi aut quo hic nihil recusandae adipisci? Recusandae itaque, sed voluptas deleniti obcaecati iure doloremque! Id ullam ipsa officiis autem voluptatibus, beatae perferendis ad
      asperiores iure voluptatum soluta aspernatur alias? Quos mollitia aliquid quia possimus quam deleniti ipsum expedita esse explicabo vel facere praesentium deserunt consequuntur nulla quisquam, voluptas iste quaerat, omnis reprehenderit labore minus repudiandae fugit! Adipisci beatae consequatur nulla harum vero reiciendis delectus, eligendi totam magni natus a esse ut deleniti nemo quis distinctio quia voluptas, aliquid ipsa consequuntur ipsam debitis commodi inventore. Quas sit quod corporis odit delectus maxime esse, quaerat ipsam officia error aspernatur neque quae dicta autem necessitatibus nemo? Rem maxime doloremque quod doloribus! Delectus doloremque accusamus quidem sed, accusantium nostrum quae ducimus perspiciatis architecto tempora? Beatae, pariatur excepturi! Blanditiis cum ullam nihil perferendis accusantium corporis in veritatis suscipit, debitis voluptates reprehenderit ex?
   </p>
 </div>


</transition>
  </div>
</template>
<script>
export default {
name:"AboutView",
data(){
  return{
    readmore:false,
    linktitle:'Read More'
  }
},
computed:{
  linkTitle(){
    if(this.readmore)
    return "Read Less";
    else
    return"Read MORE";
  }
}
}
</script>


