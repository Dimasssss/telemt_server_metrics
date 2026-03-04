# Server Metrics 2026-03-04 11:22:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 51095.0 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808049
telemt_connections_bad_total 11665
telemt_handshake_timeouts_total 10895
telemt_upstream_connect_attempt_total 32165
telemt_upstream_connect_success_total 32028
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 32028
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 357
telemt_me_reconnect_attempts_total 7081
telemt_me_reconnect_success_total 7035
telemt_me_reader_eof_total 7254
telemt_me_idle_close_by_peer_total 7254
telemt_me_route_drop_no_conn_total 314616
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1325
telemt_desync_full_logged_total 446
telemt_desync_suppressed_total 879
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 511
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 12
telemt_pool_force_close_total 492
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7254
telemt_me_writer_restored_same_endpoint_total 7014
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 657947
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 7213319328 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 199240807676 (185.56 GB)
telemt_user_unique_ips_current{user="hello"} 78
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 51091.5 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321520
telemt_connections_bad_total 2913
telemt_handshake_timeouts_total 27235
telemt_upstream_connect_attempt_total 98446
telemt_upstream_connect_success_total 96950
telemt_upstream_connect_fail_total 710
telemt_upstream_connect_attempts_per_request{bucket="1"} 96944
telemt_upstream_connect_attempts_per_request{bucket="2"} 716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 710
telemt_me_keepalive_timeout_total 1374
telemt_me_reconnect_attempts_total 55712
telemt_me_reconnect_success_total 55626
telemt_me_reader_eof_total 57040
telemt_me_idle_close_by_peer_total 57039
telemt_me_route_drop_no_conn_total 138901
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 611
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 397
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 57120
telemt_me_writer_restored_same_endpoint_total 55601
telemt_me_writer_removed_unexpected_minus_restored_total 1519
telemt_user_connections_total{user="hello"} 246163
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 3250758836 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 79731545056 (74.26 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 51090.3 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624677
telemt_connections_bad_total 153687
telemt_handshake_timeouts_total 19164
telemt_upstream_connect_attempt_total 77454
telemt_upstream_connect_success_total 77006
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 77005
telemt_upstream_connect_attempts_per_request{bucket="2"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 998
telemt_me_reconnect_attempts_total 36473
telemt_me_reconnect_success_total 36382
telemt_me_reader_eof_total 38334
telemt_me_idle_close_by_peer_total 38330
telemt_me_route_drop_no_conn_total 235051
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1125
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 409
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 38346
telemt_me_writer_restored_same_endpoint_total 36361
telemt_me_writer_removed_unexpected_minus_restored_total 1985
telemt_user_connections_total{user="hello"} 432668
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 5665494640 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 145794733924 (135.78 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 51089.2 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405879
telemt_connections_bad_total 28091
telemt_handshake_timeouts_total 66354
telemt_upstream_connect_attempt_total 38092
telemt_upstream_connect_success_total 37941
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 37941
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 428
telemt_me_reconnect_attempts_total 8212
telemt_me_reconnect_success_total 8184
telemt_me_reader_eof_total 8367
telemt_me_idle_close_by_peer_total 8367
telemt_me_route_drop_no_conn_total 115225
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 230
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8367
telemt_me_writer_restored_same_endpoint_total 8163
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 289270
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 3569091056 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 107853221996 (100.45 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 51087.9 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546635
telemt_connections_bad_total 6814
telemt_handshake_timeouts_total 132440
telemt_upstream_connect_attempt_total 72628
telemt_upstream_connect_success_total 72135
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 72135
telemt_upstream_connect_attempts_per_request{bucket="2"} 234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28392
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 946
telemt_me_reconnect_attempts_total 34994
telemt_me_reconnect_success_total 34961
telemt_me_reader_eof_total 36674
telemt_me_idle_close_by_peer_total 36673
telemt_me_route_drop_no_conn_total 173426
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 214
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 742
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 507
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 36686
telemt_me_writer_restored_same_endpoint_total 34936
telemt_me_writer_removed_unexpected_minus_restored_total 1750
telemt_user_connections_total{user="hello"} 382962
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 5036486680 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 102668313444 (95.62 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 61
```