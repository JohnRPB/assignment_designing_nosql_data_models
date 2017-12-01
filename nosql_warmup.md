# Basic

[
  {userid: 23412,
   main: {
      loggedInfo: {
        userid: 23412,
        birthday: ...,
        gender: ...,
        phone_number: ...,
        city:
        state:
        country:
        }
      },
      publicStatus:{
        loggedInfo: {
        userid: 23412,
        birthday: ...,
        gender: ...,
        phone_number: ...,
        city:
        state:
        country:
        }
      }
    }
    

  }

]

# Intermediate

## Restaurant

// collection
[
  // current snapshot of restaurant
  {
  tableIDs: {123: true, 456:true, 789:false, ...},
  users: {
          312:{reservedTable:123, reserved:true}, 
          312:{reservedTable:123, reserved:true}, 
          312:{reservedTable:123, reserved:true}
         },
  reservations:[{reserverName:,reserverPhone:,numGuests:, reservationTime:}]
  },
  // schedule to update current snapshot object
  {
    tableSchedule: {
       123: [{start: , end: }, {start: , end: }],
       456: [{start: , end: }, {start: , end: }]
    }
  }
]

## University


