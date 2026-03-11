# Server Metrics 2026-03-11 16:48:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 94912.2 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2371880
telemt_connections_bad_total 41015
telemt_handshake_timeouts_total 54103
telemt_upstream_connect_attempt_total 19853
telemt_upstream_connect_success_total 19841
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9741
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5074
telemt_me_reconnect_attempts_total 32904
telemt_me_reconnect_success_total 15029
telemt_me_reader_eof_total 16294
telemt_me_idle_close_by_peer_total 16294
telemt_me_route_drop_no_conn_total 880700
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2170691
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11254
telemt_desync_full_logged_total 3075
telemt_desync_suppressed_total 8179
telemt_desync_frames_bucket_total{bucket="1_2"} 2775
telemt_desync_frames_bucket_total{bucket="3_10"} 4345
telemt_desync_frames_bucket_total{bucket="gt_10"} 4134
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15755
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15023
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 2169141
telemt_user_connections_current{user="hello"} 1249
telemt_user_octets_from_client{user="hello"} 29189582344 (27.18 GB)
telemt_user_octets_to_client{user="hello"} 611916539056 (569.89 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 94968.8 (26h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891722
telemt_connections_bad_total 15589
telemt_handshake_timeouts_total 74922
telemt_upstream_connect_attempt_total 29964
telemt_upstream_connect_success_total 27004
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 29964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2654
telemt_me_reconnect_attempts_total 21377
telemt_me_reconnect_success_total 19276
telemt_me_reader_eof_total 20387
telemt_me_idle_close_by_peer_total 20384
telemt_me_route_drop_no_conn_total 340676
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 745817
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2989
telemt_desync_full_logged_total 955
telemt_desync_suppressed_total 2034
telemt_desync_frames_bucket_total{bucket="1_2"} 910
telemt_desync_frames_bucket_total{bucket="3_10"} 1074
telemt_desync_frames_bucket_total{bucket="gt_10"} 1005
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19550
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19253
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 748276
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 8585851722 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 211216803368 (196.71 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 94969.0 (26h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1520706
telemt_connections_bad_total 8973
telemt_handshake_timeouts_total 125988
telemt_upstream_connect_attempt_total 24517
telemt_upstream_connect_success_total 24205
telemt_upstream_connect_fail_total 312
telemt_upstream_connect_attempts_per_request{bucket="1"} 24517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 312
telemt_me_keepalive_timeout_total 1753
telemt_me_reconnect_attempts_total 42091
telemt_me_reconnect_success_total 18335
telemt_me_reader_eof_total 19894
telemt_me_idle_close_by_peer_total 19894
telemt_me_route_drop_no_conn_total 555998
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1330104
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3464
telemt_desync_full_logged_total 1026
telemt_desync_suppressed_total 2438
telemt_desync_frames_bucket_total{bucket="1_2"} 864
telemt_desync_frames_bucket_total{bucket="3_10"} 1305
telemt_desync_frames_bucket_total{bucket="gt_10"} 1295
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19329
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18323
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 994
telemt_user_connections_total{user="hello"} 1329809
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 16238961081 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 402805061069 (375.14 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 94969.3 (26h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1095612
telemt_connections_bad_total 77986
telemt_handshake_timeouts_total 105157
telemt_upstream_connect_attempt_total 25595
telemt_upstream_connect_success_total 25595
telemt_upstream_connect_attempts_per_request{bucket="1"} 25595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1164
telemt_me_reconnect_attempts_total 22985
telemt_me_reconnect_success_total 20851
telemt_me_reader_eof_total 22109
telemt_me_idle_close_by_peer_total 22108
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 360054
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879359
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1826
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 1122
telemt_desync_frames_bucket_total{bucket="1_2"} 656
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 21138
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 20820
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 878664
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 10563239032 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 259380144480 (241.57 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 94969.0 (26h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1208283
telemt_connections_bad_total 6958
telemt_handshake_timeouts_total 11920
telemt_upstream_connect_attempt_total 25984
telemt_upstream_connect_success_total 25869
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 25984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2152
telemt_me_reconnect_attempts_total 25075
telemt_me_reconnect_success_total 20976
telemt_me_reader_eof_total 22092
telemt_me_idle_close_by_peer_total 22092
telemt_me_route_drop_no_conn_total 430906
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1101247
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4303
telemt_desync_full_logged_total 1541
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1414
telemt_desync_frames_bucket_total{bucket="3_10"} 1607
telemt_desync_frames_bucket_total{bucket="gt_10"} 1282
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 21378
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20976
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 402
telemt_user_connections_total{user="hello"} 1100944
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 20547601507 (19.14 GB)
telemt_user_octets_to_client{user="hello"} 382162054342 (355.92 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 91
```