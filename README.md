# Server Metrics 2026-03-11 11:57:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 77447.4 (21h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1761930
telemt_connections_bad_total 25418
telemt_handshake_timeouts_total 45487
telemt_upstream_connect_attempt_total 16103
telemt_upstream_connect_success_total 16094
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 828
telemt_me_reconnect_attempts_total 25015
telemt_me_reconnect_success_total 12193
telemt_me_reader_eof_total 13191
telemt_me_idle_close_by_peer_total 13191
telemt_me_route_drop_no_conn_total 647479
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1604914
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8430
telemt_desync_full_logged_total 2267
telemt_desync_suppressed_total 6163
telemt_desync_frames_bucket_total{bucket="1_2"} 2112
telemt_desync_frames_bucket_total{bucket="3_10"} 3229
telemt_desync_frames_bucket_total{bucket="gt_10"} 3089
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 12721
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12187
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 528
telemt_user_connections_total{user="hello"} 1603463
telemt_user_connections_current{user="hello"} 1397
telemt_user_octets_from_client{user="hello"} 20729828848 (19.31 GB)
telemt_user_octets_to_client{user="hello"} 456787486532 (425.42 GB)
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 77504.2 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 665350
telemt_connections_bad_total 12021
telemt_handshake_timeouts_total 42346
telemt_upstream_connect_attempt_total 25410
telemt_upstream_connect_success_total 22471
telemt_upstream_connect_fail_total 2939
telemt_upstream_connect_attempts_per_request{bucket="1"} 25410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9915
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2939
telemt_me_keepalive_timeout_total 2195
telemt_me_reconnect_attempts_total 16473
telemt_me_reconnect_success_total 15622
telemt_me_reader_eof_total 16521
telemt_me_idle_close_by_peer_total 16519
telemt_me_route_drop_no_conn_total 267620
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563734
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2572
telemt_desync_full_logged_total 809
telemt_desync_suppressed_total 1763
telemt_desync_frames_bucket_total{bucket="1_2"} 827
telemt_desync_frames_bucket_total{bucket="3_10"} 937
telemt_desync_frames_bucket_total{bucket="gt_10"} 808
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 15816
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15600
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 565959
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 6016727026 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 160374332288 (149.36 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 77504.2 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1162353
telemt_connections_bad_total 7885
telemt_handshake_timeouts_total 109690
telemt_upstream_connect_attempt_total 20854
telemt_upstream_connect_success_total 20601
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 20854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 840
telemt_me_reconnect_attempts_total 29245
telemt_me_reconnect_success_total 15615
telemt_me_reader_eof_total 16763
telemt_me_idle_close_by_peer_total 16763
telemt_me_route_drop_no_conn_total 388697
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 999037
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2703
telemt_desync_full_logged_total 804
telemt_desync_suppressed_total 1899
telemt_desync_frames_bucket_total{bucket="1_2"} 635
telemt_desync_frames_bucket_total{bucket="3_10"} 1016
telemt_desync_frames_bucket_total{bucket="gt_10"} 1052
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 16245
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15604
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 999774
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 11631147973 (10.83 GB)
telemt_user_octets_to_client{user="hello"} 302505619229 (281.73 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 77504.5 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 837029
telemt_connections_bad_total 72758
telemt_handshake_timeouts_total 76298
telemt_upstream_connect_attempt_total 20922
telemt_upstream_connect_success_total 20922
telemt_upstream_connect_attempts_per_request{bucket="1"} 20922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 846
telemt_me_reconnect_attempts_total 18098
telemt_me_reconnect_success_total 17037
telemt_me_reader_eof_total 18087
telemt_me_idle_close_by_peer_total 18086
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 266854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664262
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1439
telemt_desync_full_logged_total 556
telemt_desync_suppressed_total 883
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17243
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17011
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 663628
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 7564723524 (7.05 GB)
telemt_user_octets_to_client{user="hello"} 188512364016 (175.57 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 77504.4 (21h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 902896
telemt_connections_bad_total 6244
telemt_handshake_timeouts_total 8656
telemt_upstream_connect_attempt_total 21241
telemt_upstream_connect_success_total 21148
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 894
telemt_me_reconnect_attempts_total 21220
telemt_me_reconnect_success_total 17160
telemt_me_reader_eof_total 18109
telemt_me_idle_close_by_peer_total 18109
telemt_me_route_drop_no_conn_total 316881
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 819882
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3368
telemt_desync_full_logged_total 1250
telemt_desync_suppressed_total 2118
telemt_desync_frames_bucket_total{bucket="1_2"} 1151
telemt_desync_frames_bucket_total{bucket="3_10"} 1315
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17505
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17160
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 345
telemt_user_connections_total{user="hello"} 819639
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 12280162319 (11.44 GB)
telemt_user_octets_to_client{user="hello"} 297892056030 (277.43 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 90
```