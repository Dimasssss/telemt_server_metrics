# Server Metrics 2026-03-04 16:29:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 69544.4 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1338718
telemt_connections_bad_total 18541
telemt_handshake_timeouts_total 22971
telemt_upstream_connect_attempt_total 40766
telemt_upstream_connect_success_total 40579
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 40579
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 458
telemt_me_reconnect_attempts_total 8765
telemt_me_reconnect_success_total 8697
telemt_me_reader_eof_total 8987
telemt_me_idle_close_by_peer_total 8986
telemt_me_route_drop_no_conn_total 524055
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 272
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2855
telemt_desync_full_logged_total 910
telemt_desync_suppressed_total 1945
telemt_desync_frames_bucket_total{bucket="1_2"} 822
telemt_desync_frames_bucket_total{bucket="3_10"} 1066
telemt_desync_frames_bucket_total{bucket="gt_10"} 967
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8987
telemt_me_writer_restored_same_endpoint_total 8675
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 1090583
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 14537363540 (13.54 GB)
telemt_user_octets_to_client{user="hello"} 364874060656 (339.82 GB)
telemt_user_unique_ips_current{user="hello"} 100
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 69540.8 (19h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510158
telemt_connections_bad_total 5360
telemt_handshake_timeouts_total 30699
telemt_upstream_connect_attempt_total 124321
telemt_upstream_connect_success_total 122555
telemt_upstream_connect_fail_total 844
telemt_upstream_connect_attempts_per_request{bucket="1"} 122549
telemt_upstream_connect_attempts_per_request{bucket="2"} 850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 844
telemt_me_keepalive_timeout_total 1635
telemt_me_reconnect_attempts_total 67709
telemt_me_reconnect_success_total 67602
telemt_me_reader_eof_total 69339
telemt_me_idle_close_by_peer_total 69338
telemt_me_route_drop_no_conn_total 211145
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 290
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1318
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 918
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 158
telemt_me_writer_removed_unexpected_total 69419
telemt_me_writer_restored_same_endpoint_total 67576
telemt_me_writer_removed_unexpected_minus_restored_total 1843
telemt_user_connections_total{user="hello"} 409489
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 6129364996 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 128461795684 (119.64 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 69539.8 (19h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1029093
telemt_connections_bad_total 205742
telemt_handshake_timeouts_total 30358
telemt_upstream_connect_attempt_total 90455
telemt_upstream_connect_success_total 89831
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 89830
telemt_upstream_connect_attempts_per_request{bucket="2"} 303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_keepalive_timeout_total 1179
telemt_me_reconnect_attempts_total 40245
telemt_me_reconnect_success_total 40138
telemt_me_reader_eof_total 42262
telemt_me_idle_close_by_peer_total 42257
telemt_me_route_drop_no_conn_total 381006
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 286
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2146
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1434
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42275
telemt_me_writer_restored_same_endpoint_total 40116
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 744387
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 14551544704 (13.55 GB)
telemt_user_octets_to_client{user="hello"} 255417014096 (237.88 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 16216.9 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264861
telemt_connections_bad_total 32123
telemt_handshake_timeouts_total 6480
telemt_upstream_connect_attempt_total 6367
telemt_upstream_connect_success_total 6367
telemt_upstream_connect_attempts_per_request{bucket="1"} 6367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2796
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 873
telemt_me_reconnect_success_total 880
telemt_me_reader_eof_total 890
telemt_me_idle_close_by_peer_total 890
telemt_me_route_drop_no_conn_total 88205
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 251
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 890
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 217083
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 2813290768 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 82274368024 (76.62 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 16576.8 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283480
telemt_connections_bad_total 2906
telemt_handshake_timeouts_total 4071
telemt_upstream_connect_attempt_total 8024
telemt_upstream_connect_success_total 7983
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 7983
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 1348
telemt_me_reconnect_success_total 1352
telemt_me_reader_eof_total 1379
telemt_me_idle_close_by_peer_total 1379
telemt_me_route_drop_no_conn_total 109973
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 537
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1379
telemt_me_writer_restored_same_endpoint_total 1331
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 244235
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 3979608068 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 72607962412 (67.62 GB)
telemt_user_unique_ips_current{user="hello"} 48
```