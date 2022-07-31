<template>
    <div class="container contact">
        <div class="card contact-card">
            <div class="row">
                <div class="col-6 contact-info">
                    <h3 class="title mb-4">Let's get in touch</h3>
                    <div class="row">
                        <div class="col-1">
                            <img src="../../assets/contact/map.png" class="icon" alt="Map" />
                        </div>
                        <div class="col-11">
                            <p>Sidoarjo</p>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-1">
                            <img src="../../assets/contact/gmail.png" class="icon" alt="Gmail" />
                        </div>
                        <div class="col-11">
                            <p>email@email.com</p>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-1">
                            <img src="../../assets/contact/telephone.png" class="icon" alt="Telephone" />
                        </div>
                        <div class="col-11">
                            <p>0812 3456 7890</p>
                        </div>
                    </div>
                </div>

                <div class="col-6 contact-form">
                    <h3 class="title mb-4">Contact Us</h3>
                    <form>
                        <div class="form-group mb-4">
                            <label for="name">Name</label>
                            <input type="text" class="form-control" id="name" placeholder="Enter name">
                        </div>
                        <div class="form-group mb-4">
                            <label for="email">Email</label>
                            <input type="email" class="form-control" id="email" placeholder="Enter email">
                        </div>
                        <div class="form-group mb-4">
                            <label for="message">Message</label>
                            <textarea class="form-control" id="message" placeholder="Message"></textarea>
                        </div>
                        <button type="submit" class="btn btn-success mb-4">Submit</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.contact {
    padding: 20px 40px 20px 40px;
}

.contact-card {
    padding: 20px;
}

.icon {
    width: 30px;
}
</style>