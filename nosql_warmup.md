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
  // current snapshot of restaurant - could be updated in the backend instead
  {
  tableIDs: {123: true, 456:true, 789:false, ...},
  users: {
          312:{reservedTable:123, reserved:true},
          312:{reservedTable:123, reserved:true},
          312:{reservedTable:123, reserved:true}
         },
  reservations:[]
  },
  // schedule to update current snapshot object
  {
    tableSchedule: {
       123: [
       {start: ,
         end: ,
         reservationDetails: {reserverName: ,reserverPhone: ,numGuests: , reservationTime: }
         },
       {start: ,
         end: ,
         reservationDetails: {reserverName: ,reserverPhone: ,numGuests: , reservationTime: }
         }],
       547: [
       {start: ,
         end: ,
         reservationDetails: {reserverName: ,reserverPhone: ,numGuests: , reservationTime: }
         },
       {start: ,
         end: ,
         reservationDetails: {reserverName: ,reserverPhone: ,numGuests: , reservationTime: }
         }],
    }
  }
]

## University

//students collection
{
  sid: 2342342,
  username: 'kdkd@gmail.com',
  password: 'ksdkfjsdf',
  semester: [
    {
      semesterdate: "summer 2017",
      classes:  [{
          classname: 'business',
          classid: 29834823,
          classgrade: '',
          exams: [{
            name: ''
            grade: ''
            date: '01-04-1964'
            }]
        },
        {
          classname: 'music discipline',
          classid: 29834323,
          classgrade: '',
          exams: [{
            name: ''
            grade: ''
            date: '01-04-1964'
            }]
        }]
    }
  ]
}

#Advanced

##eCommerce

//the collection of products
products: [{
  name:
  description:
  department:
  productid: 234324,
  }, {...}, {...}]

//a historical log of the products array  
{
  productid: {
    'date': [{
      name:
      description:
      department:
      productid: 234324,
      }, {...}, {...}],
    'date': [{
      name:
      description:
      department:
      productid: 234324,
      }, {...}, {...}]
  },
  productid: {
    'date': [{
      name:
      description:
      department:
      productid: 234324,
      }, {...}, {...}],
    'date': [{
      name:
      description:
      department:
      productid: 234324,
      }, {...}, {...}]
  },
}

//collection of reciepts
{
  8923849237: {
    date:
    productids:
    cost:
  }
}

//for revenue calculation
get date
look through reciepts for date range
add up costs

##Social Media
//rank

user object:
{
  activities: {
    2342343: {
      action: {type: 'post', postid: 987238942, wholiked: [23423, 234234, 45345] },
      date: '8383'
    },
    9238492: {
      action: {type: 'like', postid: 2423423},
      date: '8383'
    },
    89237984: {
      action: {type: 'comment', commentid: 2423423},
      date: '8383'
    }
  },
  friends: [{userid: 823748797, rank: 1}, {userid: 823742797, rank: 2}]
}
