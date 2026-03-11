# Server Metrics 2026-03-11 06:01:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 56050.7 (15h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1098365
telemt_connections_bad_total 13232
telemt_handshake_timeouts_total 38074
telemt_upstream_connect_attempt_total 11922
telemt_upstream_connect_success_total 11913
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 687
telemt_me_reconnect_attempts_total 20731
telemt_me_reconnect_success_total 9050
telemt_me_reader_eof_total 9847
telemt_me_idle_close_by_peer_total 9847
telemt_me_route_drop_no_conn_total 404095
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 985186
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4557
telemt_desync_full_logged_total 1288
telemt_desync_suppressed_total 3269
telemt_desync_frames_bucket_total{bucket="1_2"} 1247
telemt_desync_frames_bucket_total{bucket="3_10"} 1726
telemt_desync_frames_bucket_total{bucket="gt_10"} 1584
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9498
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9044
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 984857
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 13249768000 (12.34 GB)
telemt_user_octets_to_client{user="hello"} 289162562240 (269.30 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56107.4 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423022
telemt_connections_bad_total 3982
telemt_handshake_timeouts_total 20455
telemt_upstream_connect_attempt_total 20549
telemt_upstream_connect_success_total 17642
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 2006
telemt_me_reconnect_attempts_total 12690
telemt_me_reconnect_success_total 11867
telemt_me_reader_eof_total 12541
telemt_me_idle_close_by_peer_total 12539
telemt_me_route_drop_no_conn_total 195443
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362611
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1904
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 1336
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 684
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12003
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11845
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 364882
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 3681954342 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 89513444504 (83.37 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 56107.3 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722558
telemt_connections_bad_total 6073
telemt_handshake_timeouts_total 39730
telemt_upstream_connect_attempt_total 15220
telemt_upstream_connect_success_total 15019
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 15220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 692
telemt_me_reconnect_attempts_total 22192
telemt_me_reconnect_success_total 11119
telemt_me_reader_eof_total 11998
telemt_me_idle_close_by_peer_total 11998
telemt_me_route_drop_no_conn_total 243510
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645457
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1841
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1309
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 11609
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11108
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 646311
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 7764230761 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 191222315453 (178.09 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 56107.9 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549794
telemt_connections_bad_total 52675
telemt_handshake_timeouts_total 57342
telemt_upstream_connect_attempt_total 16113
telemt_upstream_connect_success_total 16113
telemt_upstream_connect_attempts_per_request{bucket="1"} 16113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 640
telemt_me_reconnect_attempts_total 14332
telemt_me_reconnect_success_total 13287
telemt_me_reader_eof_total 14108
telemt_me_idle_close_by_peer_total 14108
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 162577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424922
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 13440
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13265
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 424499
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 5126399756 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 117273050820 (109.22 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56107.5 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573663
telemt_connections_bad_total 5959
telemt_handshake_timeouts_total 3889
telemt_upstream_connect_attempt_total 16032
telemt_upstream_connect_success_total 15965
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 16032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 658
telemt_me_reconnect_attempts_total 16881
telemt_me_reconnect_success_total 13097
telemt_me_reader_eof_total 13833
telemt_me_idle_close_by_peer_total 13833
telemt_me_route_drop_no_conn_total 187479
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524266
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2540
telemt_desync_full_logged_total 981
telemt_desync_suppressed_total 1559
telemt_desync_frames_bucket_total{bucket="1_2"} 915
telemt_desync_frames_bucket_total{bucket="3_10"} 1084
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 13382
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13097
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 523934
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 9297663276 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 182886084444 (170.33 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 98
```