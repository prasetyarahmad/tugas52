<script setup>
import TheWelcome from '@/components/TheWelcome.vue'
</script>

<template>
    <div class="container-fluid">
      <div class="container">
        <div class="row mt-5">
          <div class="col-md-8">
            <h2>Daftar Pengguna</h2>
          </div>
          <div class="col-md-4">
            <button class="btn btn-primary btn-right">Buat Pengguna</button>
          </div>
        </div>
        <div class="row">
          <div class="table-responsive border rounded">
            <table class="table table-striped mt-3">
              <thead class="border-top">
                <tr>
                  <th>No</th>
                  <th>Name</th>
                  <th>Email</th>
                  <th>Gender</th>
                  <th>Status</th>
                  <th>Actions</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>{{arrayNo[0]}}</td>
                  <td>{{arrayNama[0]}}</td>
                  <td>{{arrayEmail[0]}}</td>
                  <td>{{arrayGender[0]}}</td>
                  <td>{{arrayStatus[0]}}</td>
                  <td>
                    <button class="btn btn-info">View</button>
                    <button class="btn btn-warning">Update</button>
                    <button class="btn btn-danger">Delete</button>
                  </td>
                </tr>
                <tr>
                  <td>{{arrayNo[1]}}</td>
                  <td>{{arrayNama[1]}}</td>
                  <td>{{arrayEmail[1]}}</td>
                  <td>{{arrayGender[1]}}</td>
                  <td>{{arrayStatus[1]}}</td>
                  <td>
                    <button class="btn btn-info">View</button>
                    <button class="btn btn-warning">Update</button>
                    <button class="btn btn-danger">Delete</button>
                  </td>
                </tr>
                <tr>
                  <td>{{arrayNo[2]}}</td>
                  <td>{{arrayNama[2]}}</td>
                  <td>{{arrayEmail[2]}}</td>
                  <td>{{arrayGender[2]}}</td>
                  <td>{{arrayStatus[2]}}</td>
                  <td>
                    <button class="btn btn-info">View</button>
                    <button class="btn btn-warning">Update</button>
                    <button class="btn btn-danger">Delete</button>
                  </td>
                </tr>
                <tr>
                  <td>{{arrayNo[3]}}</td>
                  <td>{{arrayNama[3]}}</td>
                  <td>{{arrayEmail[3]}}</td>
                  <td>{{arrayGender[3]}}</td>
                  <td>{{arrayStatus[3]}}</td>
                  <td>
                    <button class="btn btn-info">View</button>
                    <button class="btn btn-warning">Update</button>
                    <button class="btn btn-danger">Delete</button>
                  </td>
                </tr>
                <tr>
                  <td>{{arrayNo[4]}}</td>
                  <td>{{arrayNama[4]}}</td>
                  <td>{{arrayEmail[4]}}</td>
                  <td>{{arrayGender[4]}}</td>
                  <td>{{arrayStatus[4]}}</td>
                  <td>
                    <button class="btn btn-info">View</button>
                    <button class="btn btn-warning">Update</button>
                    <button class="btn btn-danger">Delete</button>
                  </td>
                </tr>
                <tr>
                  <td>{{arrayNo[5]}}</td>
                  <td>{{arrayNama[5]}}</td>
                  <td>{{arrayEmail[5]}}</td>
                  <td>{{arrayGender[5]}}</td>
                  <td>{{arrayStatus[5]}}</td>
                  <td>
                    <button class="btn btn-info">View</button>
                    <button class="btn btn-warning">Update</button>
                    <button class="btn btn-danger">Delete</button>
                  </td>
                </tr>
                <tr>
                  <td>{{arrayNo[6]}}</td>
                  <td>{{arrayNama[6]}}</td>
                  <td>{{arrayEmail[6]}}</td>
                  <td>{{arrayGender[6]}}</td>
                  <td>{{arrayStatus[6]}}</td>
                  <td>
                    <button class="btn btn-info">View</button>
                    <button class="btn btn-warning">Update</button>
                    <button class="btn btn-danger">Delete</button>
                  </td>
                </tr>
                <tr>
                  <td>{{arrayNo[7]}}</td>
                  <td>{{arrayNama[7]}}</td>
                  <td>{{arrayEmail[7]}}</td>
                  <td>{{arrayGender[7]}}</td>
                  <td>{{arrayStatus[7]}}</td>
                  <td>
                    <button class="btn btn-info">View</button>
                    <button class="btn btn-warning">Update</button>
                    <button class="btn btn-danger">Delete</button>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        
      </div>
    </div>
</template>

<script>

export default {
  name: 'HomeView',
  components:{

  },
  data: function(){
    return{
      arrayNo:["1","2","3","4","6","7","8"],
      arrayNama:["Ambar Somayaji","Atmananda Pilla","Aaryan Guneta DDS","Karunanindhi Pilla","Balachandra Kakkar","Kamlesh Mehra","Sarada Uchiha", "Chandranath Desai"],
      arrayEmail:["somayaji_ambar@mail.com","atmananda_pilla@mail.com","aaryan_guneta_dds@mail.com",
      "karunanindhi_namanyasusah@mail.com","balachandra_kakkar@mail.com","kamlesh_mehra@gmail.com","sarada_uchiha@mail.com","chandranath_desai@mail.com"],
      arrayGender:["female","male","male","female","female","female","female","female"],
      arrayStatus:["inactive","active","inactive","active","inactive","active","active","inactive"]
    }
    
  }
  
}

</script>

