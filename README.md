# Server Metrics 2026-03-15 14:50:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 59783.5 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1875851
telemt_connections_bad_total 100900
telemt_handshake_timeouts_total 21270
telemt_upstream_connect_attempt_total 11914
telemt_upstream_connect_success_total 11863
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 11914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13745
telemt_me_reconnect_success_total 8854
telemt_me_reader_eof_total 9474
telemt_me_idle_close_by_peer_total 9474
telemt_me_route_drop_no_conn_total 643119
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1587958
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6069
telemt_desync_full_logged_total 1682
telemt_desync_suppressed_total 4387
telemt_desync_frames_bucket_total{bucket="1_2"} 1508
telemt_desync_frames_bucket_total{bucket="3_10"} 2334
telemt_desync_frames_bucket_total{bucket="gt_10"} 2227
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9150
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8843
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 1587552
telemt_user_connections_current{user="hello"} 2369
telemt_user_octets_from_client{user="hello"} 22598869204 (21.05 GB)
telemt_user_octets_to_client{user="hello"} 620127064132 (577.54 GB)
telemt_user_unique_ips_current{user="hello"} 676
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 59784.5 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758106
telemt_connections_bad_total 40801
telemt_handshake_timeouts_total 58279
telemt_upstream_connect_attempt_total 15140
telemt_upstream_connect_success_total 15067
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 15140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11811
telemt_me_reconnect_success_total 11716
telemt_me_reader_eof_total 12384
telemt_me_idle_close_by_peer_total 12384
telemt_me_route_drop_no_conn_total 189052
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572706
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1994
telemt_desync_full_logged_total 690
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11865
telemt_me_writer_restored_same_endpoint_total 11704
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 572953
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 7970479943 (7.42 GB)
telemt_user_octets_to_client{user="hello"} 214734425052 (199.99 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 59784.4 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1645949
telemt_connections_bad_total 47103
telemt_handshake_timeouts_total 167144
telemt_upstream_connect_attempt_total 13179
telemt_upstream_connect_success_total 13117
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 13179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11339
telemt_me_reconnect_success_total 10081
telemt_me_reader_eof_total 10678
telemt_me_idle_close_by_peer_total 10678
telemt_me_route_drop_no_conn_total 444077
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1011952
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2525
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 1594
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 977
telemt_desync_frames_bucket_total{bucket="gt_10"} 967
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10257
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10062
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 1007966
telemt_user_connections_current{user="hello"} 1295
telemt_user_octets_from_client{user="hello"} 14658402688 (13.65 GB)
telemt_user_octets_to_client{user="hello"} 363047613164 (338.11 GB)
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 59784.3 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 794431
telemt_connections_bad_total 73553
telemt_handshake_timeouts_total 41151
telemt_upstream_connect_attempt_total 167431
telemt_upstream_connect_success_total 166934
telemt_upstream_connect_fail_total 497
telemt_upstream_connect_attempts_per_request{bucket="1"} 167431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 497
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52294
telemt_me_reconnect_success_total 11858
telemt_me_reader_eof_total 13454
telemt_me_idle_close_by_peer_total 13454
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 172617
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455302
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1198
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 890
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13236
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 11826
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1378
telemt_user_connections_total{user="hello"} 607237
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 11566710342 (10.77 GB)
telemt_user_octets_to_client{user="hello"} 203864452617 (189.86 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 59785.3 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806126
telemt_connections_bad_total 9415
telemt_handshake_timeouts_total 17097
telemt_upstream_connect_attempt_total 13204
telemt_upstream_connect_success_total 13133
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13803
telemt_me_reconnect_success_total 10123
telemt_me_reader_eof_total 10824
telemt_me_idle_close_by_peer_total 10824
telemt_me_route_drop_no_conn_total 200325
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658655
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2336
telemt_desync_full_logged_total 789
telemt_desync_suppressed_total 1547
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 898
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10356
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10115
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 658700
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 8249339880 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 244314905480 (227.54 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 121
```