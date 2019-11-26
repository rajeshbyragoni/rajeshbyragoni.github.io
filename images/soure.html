import { Injectable } from '@angular/core';
import {HttpClient, HttpHeaders,  HttpParams} from '@angular/common/http';
import {Observable, throwError} from 'rxjs';
import {catchError, map} from 'rxjs/operators';
import { Router, ActivatedRoute } from '@angular/router';

@Injectable({
	providedIn: 'root'
})
export class CommonService {

	constructor(private http : HttpClient, private route: ActivatedRoute, private router: Router) { }



	// login page start here ...

	getLoginData(email, password):Observable<any>{
		const url = 'https://gowtham-rest-api-crud.herokuapp.com/login';
		const data = new FormData();
		data.append('email', email);
		data.append('password', password);
		return this.http.post<any>(url, data)
		.pipe(map((Response : Response) => {
			//console.log(Response);
			return Response;
		}), catchError((error: Response) => {

			return throwError(error.status);

		}))
	}


		// register page start here ...

	
	getRegisterData(name, email, password):Observable<any> {
     
     const url ='https://gowtham-rest-api-crud.herokuapp.com/register';
     const token = localStorage.getItem('token');
     const data= new FormData();
     data.append('name', name);
     data.append('email', email);
     data.append('password', password);
     return this.http.post<any>(url, data)
     .pipe(map((Response:Response)=>{
          return Response;
     }), catchError((error:Response)=>{
           return throwError(error.status); 
     }));
	
	}


	// register page end here ....
	


	// get method start here ....

	getListData():Observable<any> {
		const url = 'https://gowtham-rest-api-crud.herokuapp.com/employees';
		const token = localStorage.getItem('token');
		const data = new FormData();
		const params = new HttpParams().set('token', token);

		return this.http.get<any>(url, {params})
		.pipe(map((Response : Response)=>{
			return Response;

		}), catchError((error: Response)=>{
			return throwError(error.status);
		}))

	}


	// post method start here ....

	addListData( name, phone, email, emp_id, company, location):Observable<any> {
		const token = localStorage.getItem('token')
		const url ='https://gowtham-rest-api-crud.herokuapp.com/employees';
		const params = new HttpParams().set('token', token);
		const data = new FormData();
		data.append('name', name);
		data.append('phone', phone);
		data.append('email', email);
		data.append('emp_id', emp_id);
		data.append('company', company);
		data.append('location', location);

		return this.http.post<any>(url, data, {params})
		.pipe(map((Response : Response) => {
			return Response;

		}), catchError((error: Response) => {

			return throwError(error.status);

		}));
	}

	// post method end here ....


	// update method start here ....


	/// get id/////

	getIdData(id):Observable<any> {
		const token = localStorage.getItem('token')
		const url ='https://gowtham-rest-api-crud.herokuapp.com/employees/' + id;
		const params = new HttpParams().set('token', token);
		return this.http.get<any>(url,  {params})
		.pipe(map((Response : Response) => {
			return Response;

		}), catchError((error: Response) => {

			return throwError(error.status);

		}));
	}


	/// get id/////

	///post data...

	updateListData(name, phone, email, emp_id, company, location, id):Observable<any> {

		const url ='https://gowtham-rest-api-crud.herokuapp.com/employees/' + id;
		const token = localStorage.getItem('token');
		const params = new HttpParams().set('token', token);
		const data = ({ name, phone, email, emp_id, company, location, id:id, token:token });
		const headers = new Headers();
		headers.append('Content-Type', 'application/json');
		return this.http.put<any>(url, data)
		.pipe(map((Response : Response) => {
			return Response;

		}), catchError((error: Response) => {

			return throwError(error.status);

		}));
	}

	///post data...



	// delete method start here ....

	deleteData(id):Observable<any> {

		const url ='https://gowtham-rest-api-crud.herokuapp.com/employees/' + id;
		const token = localStorage.getItem('token');
		const params = new HttpParams().set('token', token);
		return this.http.delete<any>(url, {params})
		.pipe(map((Response : Response) => {
			return Response;

		}), catchError((error: Response) => {

			return throwError(error.status);

		}));
	}


	// delete method end here ....


	// fileupload page start here ...

	
	postFile(name):Observable<any> {
     
     const url ='https://gowtham-rest-api-crud.herokuapp.com/fileupload';
     const token = localStorage.getItem('token');
     const data= new FormData();
     data.append('token', token);
     if (name !== undefined) {
            data.append('file', name);
        }
     return this.http.post<any>(url, data)
     .pipe(map((Response:Response)=>{
     	//console.log(Response);
          return Response;
     }), catchError((error:Response)=>{
           return throwError(error.status); 
     }));
	
	}


	// fileupload page end here ....




		// fileupload listdata page start here ...

	
	
	/// get id/////

	getFile():Observable<any> {
		const token = localStorage.getItem('token')
		const url ='https://gowtham-rest-api-crud.herokuapp.com/fileupload';
		const params = new HttpParams().set('token', token);
		return this.http.get<any>(url,  {params})
		.pipe(map((Response : Response) => {
			return Response;

		}), catchError((error: Response) => {

			return throwError(error.status);

		}));
	}


	/// get id/////


	/// deletelist data id/////

	deleteFile(id):Observable<any> {
		const token = localStorage.getItem('token')
		const url ='https://gowtham-rest-api-crud.herokuapp.com/filedelete/'+ id;
		const params = new HttpParams().set('token', token);
		return this.http.delete<any>(url,  {params})
		.pipe(map((Response : Response) => {
			return Response;

		}), catchError((error: Response) => {

			return throwError(error.status);

		}));
	}


	/// deletelist data id/////


	// fileupload listdata page end here ....


}


<td><a routerLink="/edit" [queryParams]="{id:emlys.id}">Edit</a>
<a class="btn btn-sm btn-danger" (click)="deleteData(emlys.id)">Delete 
<i class="fa fa-spinner fa-spin" id="{{emlys.id}}" style="display:none;"></i></a></td>



/********* edit *********/
ngOnInit() {
		this.routef.queryParams.subscribe(
			reult => {

				this.id = reult['id'];
				this.getIdNewData(reult['id']);

			}

			);
	}

	/********edit end *********/


/*************** fileupload start here ****/

fileToUpload: File = null;
  fileList: FileList;
  file: File;
  name :any;
  dataFile:any;
  imgData:any;
  listData:any;
  constructor(private common : CommonService, private fb : FormBuilder, private route : Router, private routef : ActivatedRoute) {
 this.createForm();
   }

  ngOnInit() {
  	this.getDataF();
  }

  

  createForm(){
  	this.fileNew = this.fb.group({
       name:['', Validators.required]
  	});
  }

fileChange(event) {
    this.fileList = event.target.files;
    if (this.fileList.length > 0) {
      this.file = this.fileList[0];
    }
    const file = event.target['files'][0];
    this.name = file;
  }

 uploadFile(){
  	this.common.postFilesD(this.file).subscribe(
         result=>{
         	console.log(result);
         	this.ngOnInit();
         }, error=>{
         	console.log(error.toString());
         }

  		)
  }