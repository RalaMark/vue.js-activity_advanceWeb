<script setup>
import { ref } from 'vue';

const inputText = ref('hello')
const town = ref('')

</script>



<template>
  
  <div class="p-3 mb-3 bg-secondary text-white ">
    <div  class="border border-warning ">
<div class="mx-auto p-2" style="width: 400px; ">
  <div  class="border border-warning ">
  <div class="text-bg-dark p-3">
   
     <label>Select Town In Sorsogon</label>
    <select v-model="town" class="form-select" aria-label="Default select example">
        <option value="bulan">Bulan</option>
        <option value="irosin">Irosin</option>
        <option value="juban">Juban</option>
        <option value="casiguran">Casiguran</option>
        <option value="matnog">Matnog</option>
        <option value="bulusan">Bulusan</option>
        <option value="castilla">Castilla</option>
        <option value="pilar">Pilar</option>
        <option value="magallanes">Magallanes</option>
        <option value="donsol">Donsol</option>
        <option value="gubat">Gubat</option>
        <option value="sta.magdalena">Sta.Magdalena</option>
        <option value="puerto">Prieto Diaz</option>
        <option value="barcelona">Barcelona</option>

    </select>

    <p v-if="town == 'bulan'" class="fst-italic mt-5">
    <h5>
     Bulan is a picturesque coastal municipality nestled in Sorsogon, Philippines, known for its stunning natural beauty and rich cultural heritage. With a backdrop of lush mountains and bordered by the tranquil waters of Sorsogon Bay, Bulan offers a serene environment for residents and visitors alike. Its economy thrives on agriculture, particularly coconut and rice farming, and the town celebrates its vibrant culture through traditional festivals and events. Bulan's coastline features pristine beaches where travelers can relax, swim, and take in breathtaking sunsets, while its warm and welcoming community adds to the charm of this idyllic coastal town, making it a delightful destination for those seeking a peaceful retreat
</h5>
    </p>
    <p v-if="town == 'irosin'" class="fst-italic mt-5">
    <h5>Irosin is the only inland town in the province and sits on a valley floor surrounded by mountains. As a valley town, it is a river basin valley owing to the numerous rivers, creeks and streams that trek down from the mountains to the valley floor.</h5>
    </p>
    <p v-if="town == 'juban'" class="fst-italic mt-5">
    <h5>Juban is a coastal municipality in the province of Sorsogon. The municipality has a land area of 121.49 square kilometers or 46.91 square miles which constitutes 5.73% of Sorsogon's total area.</h5>
    </p>
    <p v-if="town == 'casiguran'" class="fst-italic mt-5">
    <h5>Casiguran is a coastal town known for its picturesque landscapes, beautiful beaches, and lush greenery. It is nestled along the eastern coast of Sorsogon province, facing the Philippine Sea. The town's economy primarily relies on agriculture, with rice, coconut, and fishing being some of its main industries.</h5>
    </p>
    <p v-if="town == 'matnog'" class="fst-italic mt-5">
    <h5>Matnog, located in the province of Sorsogon, Philippines, is a coastal gem renowned for its breathtaking beauty and pivotal role as a transport gateway. Nestled at the southeastern tip of the Bicol Peninsula, Matnog boasts pristine white sand beaches and crystal-clear waters that beckon travelers and beach enthusiasts. Subic Beach and Tikling Island are among its renowned treasures, offering opportunities for swimming, snorkeling, and relaxation amidst stunning natural scenery. Matnog's bustling port serves as a vital link between Luzon and the Visayan islands, with ferries connecting these regions. Visitors not only revel in the area's natural splendor but also immerse themselves in the local culture, enjoying fresh seafood, exploring caves, and partaking in traditional festivals, creating an unforgettable coastal experience.</h5>
    </p>
    <p v-if="town == 'bulusan'" class="fst-italic mt-5">
    <h5>Bulusan is a picturesque town situated in Sorsogon Province, Philippines. It is known for its stunning natural landscapes and is often referred to as the "Summer Capital of Sorsogon" due to its cool and pleasant climate. One of the town's most notable features is Mount Bulusan, an active volcano surrounded by lush forests. Mount Bulusan is a popular destination for hikers and nature enthusiasts who come to explore its trails, enjoy its hot springs, and witness its occasional volcanic activity.</h5>
    </p>
    <p v-if="town == 'castilla'" class="fst-italic mt-5">
    <h5>Castilla is a quaint town nestled in the southern part of Sorsogon Province, characterized by its serene rural setting and natural beauty. The town is primarily known for its agriculture, with rice and coconut farming being key economic activities. The lush countryside and fertile lands make it an ideal location for farming.</h5>
    </p>
    <p v-if="town == 'pilar'" class="fst-itali mt-5">
    <h5>Pilar is a coastal town in Sorsogon known for its picturesque natural beauty and vibrant marine life. The town is situated along the eastern coast of the Bicol Peninsula, offering stunning views of the Philippine Sea. It is a popular destination for tourists and travelers looking to explore the underwater world and enjoy the serenity of coastal living.</h5>
    </p>
    <p v-if="town == 'magallanes'" class="fst-italic mt-5">
    <h5>Magallanes, a charming coastal municipality in Sorsogon, Philippines, captures the essence of rural living amid serene natural beauty. Located on the southeastern edge of the Bicol Peninsula, it boasts a picturesque landscape framed by the Philippine Sea to the east. The local economy thrives on agriculture, particularly rice and coconut cultivation, as well as the rich marine resources harvested through fishing and aquaculture. Visitors to Magallanes can immerse themselves in the tranquil coastal atmosphere, with opportunities for beach outings, swimming, and relaxation along its pristine shores. The town's cultural vibrancy is celebrated through traditional festivals and events, offering a glimpse into the warm and hospitable local community. Magallanes invites travelers seeking an authentic and peaceful escape amidst nature's splendor.

</h5>

    
    </p>
    <p v-if="town == 'donsol'" class="fst-italic mt-5">
    <h5>Donsol is a small coastal town in the Philippines, located in the province of Sorsogon. It is renowned worldwide as one of the best places for encountering whale sharks, gentle giants of the sea. Every year, from November to June, these magnificent creatures visit the waters off Donsol, offering a unique opportunity for tourists to swim alongside them. Donsol's commitment to responsible and sustainable ecotourism has made it a popular destination for travelers seeking an awe-inspiring and eco-friendly wildlife experience. Besides whale shark encounters, visitors can also enjoy the town's laid-back atmosphere, scenic beaches, and natural beauty, making Donsol a must-visit destination for nature enthusiasts and adventure seekers.</h5>
    </p>
    <p v-if="town == 'gubat'" class="fst-italic mt-5">
    <h5>Gubat is a coastal town located in the province of Sorsogon, Philippines. It's renowned for its stunning beaches and lush landscapes, making it a popular destination for beachgoers and nature enthusiasts. The town offers a tranquil escape with its beautiful coastlines, clear waters, and opportunities for swimming and water sports. Gubat is also known for its rich marine life, making it a great spot for snorkeling and diving. Beyond its natural beauty, the town has a vibrant local culture and traditions that visitors can experience through its festivals and warm hospitality.</h5>
    </p>
    <p v-if="town == 'sta.magdalena'" class="fst-italic mt-5">
    <h5>Santa Magdalena is a charming town situated in Sorsogon, known for its serene rural setting and natural beauty. Nestled amid the picturesque landscapes of the Bicol region, the municipality offers a glimpse into rural Philippine life. Its economy is primarily based on agriculture, with rice and coconut farming being key industries.
    The town is dotted with lush greenery, offering a tranquil atmosphere for residents and visitors. While it may not be as widely recognized as some of the more popular tourist destinations in Sorsogon, Santa Magdalena provides a peaceful escape for those seeking a quiet and authentic rural experience. It's an ideal destination to immerse oneself in the simplicity and charm of rural Philippines while enjoying the warm hospitality of the local community.

</h5>
    </p>
    <p v-if="town == 'puerto'" class="fst-italic mt-5">
    <h5>Prieto Diaz is a coastal town in Sorsogon known for its scenic beauty and relaxed atmosphere. It is bordered by the Pacific Ocean to the east, offering picturesque views of the sea. The local economy is supported by agriculture, particularly rice and coconut farming.
    The town features several beautiful beaches and coastal areas where visitors can relax, swim, and enjoy the coastal scenery. Prieto Diaz provides a serene environment, making it an ideal place for those looking to unwind and appreciate the natural beauty of the Philippines.</h5>
    </p>
   
    <p v-if="town == 'barcelona'" class="fst-italic mt-5">
    <h5>Barcelona is a coastal town in Sorsogon known for its historical significance and scenic beauty. It was named after the Spanish city of Barcelona and has retained some Spanish influences in its culture and architecture. One of the notable attractions in the town is the Barcelona Church, also known as the St. Joseph the Worker Church, which is a centuries-old church with a beautiful facade and historical significance.
      The town's economy relies on agriculture, with rice and coconut farming being prominent. Barcelona is also known for its picturesque coastline, featuring serene beaches where visitors can relax, swim, and enjoy the coastal scenery.</h5>
    </p>
    <p v-else>

      <!-- kindly select town -->
    </p>
  </div>
</div>
  </div>
</div>
</div>


</template>