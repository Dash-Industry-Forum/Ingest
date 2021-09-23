<table border=1 cellspacing=0 cellpadding=0  style='border-collapse:collapse;border:none'>
    <tr>
        <td width=790 valign=top style='border:solid 1.5pt'>
            <table border="0" cellspacing="4" cellpadding="4" width="786">
                    <tr style= "height: 20px;">
                        <td border="0"  colspan="15" valign="top"><p align="center"><strong>CHANGE REQUEST</strong></p></td>
                    </tr>
                    <tr style= "height: 10px;">
                        <td style= "height: 10px;" colspan="4" bgcolor="#FFEE58"><p align="center"><strong> DASH-IF IOP</strong></p></td> 
                        <td style= "height: 10px;" colspan="2"><p align="center"><strong>CR</strong></p></td>
                        <td style= "height: 10px;" width="60" bgcolor="#FFEE58"></td>
                        <td style= "height: 10px;"><p align="center"><strong>rev</strong></p></td>
                        <td colspan="2" bgcolor="#FFEE58"><p align="center"><strong>-</strong></p></td>
                        <td style= "height: 10px;" colspan="3"><p align="center"><strong>Current version:</strong> </p></td>
                        <td style= "height: 10px;" colspan="2" bgcolor="#FFEE58"> <p align="center"> V0.9</p></td>
                    </tr>
                    <tr height= "%10"> </tr>
                    <tr>
                        <td colspan = "2" valign="middle"><p><strong><em>Status: </em></strong></p></td>
                        <td style="border: 1px solid black"  width="20" valign="middle" bgcolor="#FFEE58"> 
                        </td>
                        <td colspan = "2" valign="middle"><p>Draft</p> </td>
                        <td style="border: 1px solid black" width="20" valign="middle" bgcolor="#FFEE58"></td>
                        <td colspan = "2" valign="top"><p>Internal Review</p></td>
                        <td  style="border: 1px solid black" width="20" valign="middle" bgcolor="#FFEE58"><p align="center">X</p></td>
                        <td colspan = "2" valign="top"><p>Community Review</p> </td>
                        <td style="border: 1px solid black" width="20" valign="middle" bgcolor="#FFEE58"> </td>
                        <td colspan = "3" valign="middle"><p>Agreed</p></td>
                    </tr>
                    <tr height= "%10"> </tr>
            </table>
        </td>
    </tr>
</table>
<br>
<table border=1 cellspacing=0 cellpadding=0  style='border-collapse:collapse;border:none'>
    <tr>
        <td width=790 valign=top style='border:solid 1.5pt'>
            <table border="0" cellspacing="4" cellpadding="4" width="786">
                <tr>
                    <td colspan="4" valign="top">
                        <p>
                            <strong><em>Title: </em></strong>
                        </p>
                    </td>
                    <td colspan="17" valign="top" bgcolor="#FFEE58">
                        <p>
                            DASH-IF Specification of Live Media Ingest
                        </p>
                    </td>
                </tr>
                <tr height= "%10"> </tr>
                <tr>
                    <td colspan="4" valign="top">
                        <p>
                            <strong><em>Source:</em></strong>
                        </p>
                    </td>
                    <td colspan="17" valign="top" bgcolor="#FFEE58">
                        <p>
                            DASH-IF IOP Ingest TF
                        </p>
                    </td>
                </tr>
                <tr height= "%10"> </tr>
                <tr>
                    <td colspan="4" valign="top">
                        <p>
                            <strong><em>Supporting Companies:</em></strong>
                        </p>
                    </td>
                    <td colspan="17" valign="top" bgcolor="#FFEE58">
                        <p>
                            CenturyLink, Qualcomm Inc., MediaExcel, Harmonic, 
                            Bitmovin, Hulu, Microsoft, Unified Streaming, Akamai, Comcast, AWS Elemental, 
                            Sony, Tencent, &lt;others&gt;
                        </p>
                    </td>
                </tr>
                <tr height= "%10"> </tr>
                <tr>
                    <td colspan="4" valign="top">
                        <p>
                            <strong><em>Category:</em></strong>
                        </p>
                    </td>
                    <td valign="top" bgcolor="#FFEE58">
                        <p>
                            <strong>A</strong>
                        </p>
                    </td>
                    <td  colspan="9" valign="top">
                    </td>
                    <td  colspan="3" valign="top">
                        <p align="right">
                            <strong><em>Date:</em></strong>
                        </p>
                    </td>
                    <td colspan="4" valign="top" bgcolor="#FFEE58">
                        <p>
                            2019-06-14
                        </p>
                    </td>
                </tr>
                <tr>
                    <td colspan="4" valign="top">
                    </td>
                    <td  colspan="11" valign="top">
                        <p>
                            <em>
                                Use <u>one</u> of the following categories:
                                <strong>
                                    <br/>
                                    C
                                </strong>
                                (correction)
                                <br/>
                                <strong>A</strong>
                                (addition of feature)
                                <br/>
                                <strong>B</strong>
                                (editorial modification)
                            </em>
                        </p>
                    </td>
                    <td colspan="6" valign="top"></td>
                </tr>
                <tr height= "%10"> </tr>
                </table>
        </td>
    </tr>
</table>
<br>
<table border=1 cellspacing=0 cellpadding=0  style='border-collapse:collapse;border:none'>
    <tr>
        <td width=790 valign=top style='border:solid 1.5pt'>
            <table border="0" cellspacing="4" cellpadding="4" width="786">
                <tr>
                    <td  width= "100" colspan="5" valign="top">
                        <p>
                            <strong><em>Reason for change:</em></strong>
                        </p>
                    </td>
                    <td colspan="16" valign="top" bgcolor="#FFEE58">
                        <p>
                            Improve interoperability between cloud and server side streaming entities. In particular, 
	                        between ABR live encoders, origin servers and content delivery networks.
                        </p>
                    </td>
                </tr>
                <tr height= "%10"> </tr>
                <tr>
                    <td  colspan="5" valign="top" >
                        <p>
                            <strong><em>Summary of change:</em></strong>
                        </p>
                    </td>
                    <td colspan="16" valign="top" bgcolor="#FFEE58">
                        <p>
                            This document specifies protocol interfaces for live ingest/egress of media content.
	                    It can be used between live ABR encoders, streaming origins, packagers and content delivery networks.
			    It features support for redundant workflows with failover support and timed metadata.
                        </p>
                    </td>
                </tr>
                <tr height= "%10"> </tr>
                <tr>
                    <td colspan="5" valign="top">
                        <p>
                            <strong><em>Consequences if not approved:</em></strong>
                        </p>
                    </td>
                    <td colspan="16" valign="top" bgcolor="#FFEE58">
                        <p>
                            Inconsistent implementations, Poor interoperability, less rich metadata and ad insertion support
                        </p>
                    </td>
                </tr>
                <tr height= "%10"> </tr>
                <tr>
                    <td colspan="5" valign="top">
                        <p>
                            <strong><em>Sections affected:</em></strong>
                        </p>
                    </td>
                    <td colspan="16" valign="top" bgcolor="#FFEE58">
                        <p>
                            New Independent Document
                        </p>
                    </td>
                </tr>
                <tr height= "%10"> </tr>
                <tr>
                    <td colspan="5" valign="top">
                        <p>
                            <strong><em>Other comments:</em></strong>
                        </p>
                    </td>
                    <td colspan="16" valign="top" bgcolor="#FFEE58">
                        <p>
                            Feedback during community review is welcome.
                        </p>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>
<br>
<table border=1 cellspacing=0 cellpadding=0  style='border-collapse:collapse;border:none'>
    <tr>
        <td width=790 valign=top style='border:solid 1.5pt'>
            <table border="0" cellspacing="4" cellpadding="4" width="786">
                <tr>
                    <td width= "100" valign="top">
                        <p>
                            <strong><em>Disclaimer:</em></strong>
                        </p>
                    </td>
                    <td valign="top" bgcolor="#FFEE58">
                        <p>
                            This document is not yet final. It is provided for public
                            review until the deadline mentioned below. If you have
                            comments on the document, please submit comments by one of
                            the following means: 
                            <ul>
                                <li> at the github repository: <a href="https://github.com/Dash-Industry-Forum/Ingest/issues">https://github.com/Dash-Industry-Forum/Ingest/issues</a>, or </li>
                                <li> dashif+iop@groupspaces.com with a subject tag [Ingest] </li>
				 <li> or for public community review comments: 
			 <a href=https://gitreports.com/issue/Dash-Industry-Forum/Ingest> community review gitreport comments </a>  
				    </li>
                            </ul>
                        </p>
                        <p> Please add a detailed description of the problem and the
                            comment.
                       </p>
                        <p>
                            Based on the received comments a final document will be
                            published latest by the expected publication date below,
                            integrated in a new version of DASH-IF IOP, if the following
                            additional criteria are fulfilled:
                           <ul>
                                <li> All comments from community review are addressed</li>
                                <li> The relevant aspects for the Conformance Software are
                            provided </li>
                                <li> Verified IOP test vectors are provided</li>
                            </ul> 
                        </p>
                    </td>
                </tr>
                <tr> <td  colspan= 2> </td></tr>
                <tr>
                    <td valign="top">
                        <p>
                            <strong><em>Commenting Deadline:</em></strong>
                        </p>
                    </td>
                    <td width="492" valign="top" bgcolor="#FFEE58">
                        <p>
                            July 31<sup>st</sup>, 2019
                        </p>
                    </td>
                </tr>
                <tr> <td colspan= 2> </td></tr>
                <tr>
                    <td valign="top">
                        <p>
                            <strong><em>Expected Publication:</em></strong>
                        </p>
                    </td>
                    <td valign="top" bgcolor="#FFEE58">
                        <p>
                            August 31<sup>st</sup>, 2019
                        </p>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>


