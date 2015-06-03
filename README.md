# SWEN-P01
protected void CRnextBTN_Click(object sender, EventArgs e)
        {
            string CRroomtype = ddlRoomType.SelectedValue;
            string CRcheckin = ddlCheckin.SelectedValue + "/" + ddlmonth.SelectedValue + "/" + tbxyear.Text;
            string CRcheckout = ddlCheckout.SelectedValue + "/" + ddlCOmonth.SelectedValue + "/" + tbxCRCOyear.Text;
            string CRadult = ddlAdults.SelectedValue;
            string CRchild = ddlChild.SelectedValue;
           string CRremarks = tbxRemarks.Text;
           string CRlaterequest = ddlLateRequest.SelectedValue;


           string querystring = "CRroomtype=" + CRroomtype;
            querystring += "&" + "CRcheckin=" + CRcheckin;
            querystring += "&" + "CRcheckout=" + CRcheckout;
            querystring += "&" + "CRadult=" + CRadult;
           querystring += "&" + "CRchild=" + CRchild;
           querystring += "&" + "CRremarks=" + CRremarks;
           querystring += "&" + "CRlaterequest=" + CRlaterequest;
}
