# Server Metrics 2026-03-04 12:18:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 54478.2 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924192
telemt_connections_bad_total 12096
telemt_handshake_timeouts_total 14133
telemt_upstream_connect_attempt_total 32853
telemt_upstream_connect_success_total 32711
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 32711
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 367
telemt_me_reconnect_attempts_total 7090
telemt_me_reconnect_success_total 7042
telemt_me_reader_eof_total 7261
telemt_me_idle_close_by_peer_total 7261
telemt_me_route_drop_no_conn_total 339540
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1500
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 993
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7261
telemt_me_writer_restored_same_endpoint_total 7020
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 731308
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 7811124928 (7.27 GB)
telemt_user_octets_to_client{user="hello"} 225237604380 (209.77 GB)
telemt_user_unique_ips_current{user="hello"} 94
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 54474.7 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365650
telemt_connections_bad_total 3202
telemt_handshake_timeouts_total 27857
telemt_upstream_connect_attempt_total 101630
telemt_upstream_connect_success_total 100062
telemt_upstream_connect_fail_total 746
telemt_upstream_connect_attempts_per_request{bucket="1"} 100056
telemt_upstream_connect_attempts_per_request{bucket="2"} 752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 746
telemt_me_keepalive_timeout_total 1411
telemt_me_reconnect_attempts_total 56999
telemt_me_reconnect_success_total 56911
telemt_me_reader_eof_total 58348
telemt_me_idle_close_by_peer_total 58347
telemt_me_route_drop_no_conn_total 150238
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 230
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 643
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58428
telemt_me_writer_restored_same_endpoint_total 56886
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 275463
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 3617626988 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 86865017400 (80.90 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 54473.5 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695063
telemt_connections_bad_total 162868
telemt_handshake_timeouts_total 22659
telemt_upstream_connect_attempt_total 79813
telemt_upstream_connect_success_total 79336
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 79335
telemt_upstream_connect_attempts_per_request{bucket="2"} 230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 1038
telemt_me_reconnect_attempts_total 37217
telemt_me_reconnect_success_total 37125
telemt_me_reader_eof_total 39101
telemt_me_idle_close_by_peer_total 39097
telemt_me_route_drop_no_conn_total 259302
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 228
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1225
telemt_desync_full_logged_total 436
telemt_desync_suppressed_total 789
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 39113
telemt_me_writer_restored_same_endpoint_total 37103
telemt_me_writer_removed_unexpected_minus_restored_total 2010
telemt_user_connections_total{user="hello"} 483318
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 11332157620 (10.55 GB)
telemt_user_octets_to_client{user="hello"} 161548535460 (150.45 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 1150.8 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13116
telemt_connections_bad_total 1275
telemt_handshake_timeouts_total 335
telemt_upstream_connect_attempt_total 362
telemt_upstream_connect_success_total 362
telemt_upstream_connect_attempts_per_request{bucket="1"} 362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 118
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 4570
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 11307
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 133117472 (126.95 MB)
telemt_user_octets_to_client{user="hello"} 7993473844 (7.44 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 1510.8 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25783
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 464
telemt_upstream_connect_attempt_total 371
telemt_upstream_connect_success_total 366
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 366
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 7904
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 75
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 4
telemt_user_connections_total{user="hello"} 22105
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 259581996 (247.56 MB)
telemt_user_octets_to_client{user="hello"} 6551218716 (6.10 GB)
telemt_user_unique_ips_current{user="hello"} 66
```