# Server Metrics 2026-03-13 10:17:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 101945.4 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2947256
telemt_connections_bad_total 36442
telemt_handshake_timeouts_total 53489
telemt_upstream_connect_attempt_total 20109
telemt_upstream_connect_success_total 20000
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1428
telemt_me_reconnect_attempts_total 24986
telemt_me_reconnect_success_total 14917
telemt_me_reader_eof_total 16068
telemt_me_idle_close_by_peer_total 16067
telemt_me_route_drop_no_conn_total 1087591
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2687114
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11731
telemt_desync_full_logged_total 3033
telemt_desync_suppressed_total 8698
telemt_desync_frames_bucket_total{bucket="1_2"} 3005
telemt_desync_frames_bucket_total{bucket="3_10"} 4400
telemt_desync_frames_bucket_total{bucket="gt_10"} 4326
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 15439
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14904
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 522
telemt_user_connections_total{user="hello"} 2687048
telemt_user_connections_current{user="hello"} 1677
telemt_user_octets_from_client{user="hello"} 36990565924 (34.45 GB)
telemt_user_octets_to_client{user="hello"} 873585688712 (813.59 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 131565.6 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1180793
telemt_connections_bad_total 15103
telemt_handshake_timeouts_total 106930
telemt_upstream_connect_attempt_total 32563
telemt_upstream_connect_success_total 32532
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3781
telemt_me_reconnect_attempts_total 24469
telemt_me_reconnect_success_total 24342
telemt_me_reader_eof_total 25954
telemt_me_idle_close_by_peer_total 25954
telemt_me_route_drop_no_conn_total 365104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1016369
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4486
telemt_desync_full_logged_total 1360
telemt_desync_suppressed_total 3126
telemt_desync_frames_bucket_total{bucket="1_2"} 1631
telemt_desync_frames_bucket_total{bucket="3_10"} 1484
telemt_desync_frames_bucket_total{bucket="gt_10"} 1371
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 24580
telemt_me_writer_restored_same_endpoint_total 24333
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 1018304
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 15458893648 (14.40 GB)
telemt_user_octets_to_client{user="hello"} 371533677951 (346.02 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 131565.5 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2285712
telemt_connections_bad_total 25079
telemt_handshake_timeouts_total 155829
telemt_upstream_connect_attempt_total 30080
telemt_upstream_connect_success_total 30070
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1877
telemt_me_reconnect_attempts_total 24445
telemt_me_reconnect_success_total 23157
telemt_me_reader_eof_total 24536
telemt_me_idle_close_by_peer_total 24535
telemt_me_route_drop_no_conn_total 748568
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1833142
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6018
telemt_desync_full_logged_total 1924
telemt_desync_suppressed_total 4094
telemt_desync_frames_bucket_total{bucket="1_2"} 979
telemt_desync_frames_bucket_total{bucket="3_10"} 2193
telemt_desync_frames_bucket_total{bucket="gt_10"} 2846
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 23389
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23116
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 1832592
telemt_user_connections_current{user="hello"} 975
telemt_user_octets_from_client{user="hello"} 31729251888 (29.55 GB)
telemt_user_octets_to_client{user="hello"} 659887238749 (614.57 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 131565.9 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1446293
telemt_connections_bad_total 14238
telemt_handshake_timeouts_total 89966
telemt_upstream_connect_attempt_total 43058
telemt_upstream_connect_success_total 40748
telemt_upstream_connect_fail_total 2173
telemt_upstream_connect_attempts_per_request{bucket="1"} 42784
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2172
telemt_me_keepalive_timeout_total 11506
telemt_me_reconnect_attempts_total 37279
telemt_me_reconnect_success_total 28330
telemt_me_reader_eof_total 30505
telemt_me_idle_close_by_peer_total 30498
telemt_me_route_drop_no_conn_total 510869
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1209022
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2273
telemt_desync_full_logged_total 750
telemt_desync_suppressed_total 1523
telemt_desync_frames_bucket_total{bucket="1_2"} 635
telemt_desync_frames_bucket_total{bucket="3_10"} 867
telemt_desync_frames_bucket_total{bucket="gt_10"} 771
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 28816
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 28306
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 1213773
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 18402078557 (17.14 GB)
telemt_user_octets_to_client{user="hello"} 482738404866 (449.59 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 131565.8 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1616768
telemt_connections_bad_total 36073
telemt_handshake_timeouts_total 13127
telemt_upstream_connect_attempt_total 42106
telemt_upstream_connect_success_total 41603
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 42106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_timeout_total 2330
telemt_me_reconnect_attempts_total 53016
telemt_me_reconnect_success_total 35038
telemt_me_reader_eof_total 36818
telemt_me_idle_close_by_peer_total 36818
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 591742
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1469571
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 5152
telemt_desync_full_logged_total 1837
telemt_desync_suppressed_total 3315
telemt_desync_frames_bucket_total{bucket="1_2"} 1591
telemt_desync_frames_bucket_total{bucket="3_10"} 1669
telemt_desync_frames_bucket_total{bucket="gt_10"} 1892
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 35980
telemt_me_refill_failed_total 557
telemt_me_writer_restored_same_endpoint_total 34977
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 942
telemt_user_connections_total{user="hello"} 1469365
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 18799501380 (17.51 GB)
telemt_user_octets_to_client{user="hello"} 513818196148 (478.53 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 54
```