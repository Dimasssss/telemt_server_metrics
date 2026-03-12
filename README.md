# Server Metrics 2026-03-12 18:50:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 46295.0 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1652082
telemt_connections_bad_total 20514
telemt_handshake_timeouts_total 15290
telemt_upstream_connect_attempt_total 9205
telemt_upstream_connect_success_total 9153
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 9205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 569
telemt_me_reconnect_attempts_total 15638
telemt_me_reconnect_success_total 6792
telemt_me_reader_eof_total 7355
telemt_me_idle_close_by_peer_total 7354
telemt_me_route_drop_no_conn_total 645840
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1544482
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7869
telemt_desync_full_logged_total 1999
telemt_desync_suppressed_total 5870
telemt_desync_frames_bucket_total{bucket="1_2"} 2043
telemt_desync_frames_bucket_total{bucket="3_10"} 2848
telemt_desync_frames_bucket_total{bucket="gt_10"} 2978
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 7163
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6779
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 1543967
telemt_user_connections_current{user="hello"} 1425
telemt_user_octets_from_client{user="hello"} 23821112996 (22.19 GB)
telemt_user_octets_to_client{user="hello"} 523516742224 (487.56 GB)
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75915.7 (21h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708129
telemt_connections_bad_total 9348
telemt_handshake_timeouts_total 29518
telemt_upstream_connect_attempt_total 19417
telemt_upstream_connect_success_total 19388
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 19417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3367
telemt_me_reconnect_attempts_total 14007
telemt_me_reconnect_success_total 13922
telemt_me_reader_eof_total 14803
telemt_me_idle_close_by_peer_total 14803
telemt_me_route_drop_no_conn_total 226004
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 637668
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2799
telemt_desync_full_logged_total 859
telemt_desync_suppressed_total 1940
telemt_desync_frames_bucket_total{bucket="1_2"} 1107
telemt_desync_frames_bucket_total{bucket="3_10"} 917
telemt_desync_frames_bucket_total{bucket="gt_10"} 775
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 14070
telemt_me_writer_restored_same_endpoint_total 13913
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 639547
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 9794027048 (9.12 GB)
telemt_user_octets_to_client{user="hello"} 240404712447 (223.89 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 75915.5 (21h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466497
telemt_connections_bad_total 6998
telemt_handshake_timeouts_total 101247
telemt_upstream_connect_attempt_total 18064
telemt_upstream_connect_success_total 18058
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1183
telemt_me_reconnect_attempts_total 15121
telemt_me_reconnect_success_total 13876
telemt_me_reader_eof_total 14636
telemt_me_idle_close_by_peer_total 14635
telemt_me_route_drop_no_conn_total 483552
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1121105
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4710
telemt_desync_full_logged_total 1451
telemt_desync_suppressed_total 3259
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 1707
telemt_desync_frames_bucket_total{bucket="gt_10"} 2264
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14002
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13835
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 1120968
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 17626699672 (16.42 GB)
telemt_user_octets_to_client{user="hello"} 407480561265 (379.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 75916.1 (21h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895067
telemt_connections_bad_total 12890
telemt_handshake_timeouts_total 66078
telemt_upstream_connect_attempt_total 19642
telemt_upstream_connect_success_total 19565
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 19642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 1628
telemt_me_reconnect_attempts_total 23474
telemt_me_reconnect_success_total 15749
telemt_me_reader_eof_total 16824
telemt_me_idle_close_by_peer_total 16824
telemt_me_route_drop_no_conn_total 315355
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 773783
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1736
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 575
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 16117
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 15728
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 773141
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 9385691304 (8.74 GB)
telemt_user_octets_to_client{user="hello"} 318203991064 (296.35 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75915.9 (21h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002334
telemt_connections_bad_total 11476
telemt_handshake_timeouts_total 8255
telemt_upstream_connect_attempt_total 23804
telemt_upstream_connect_success_total 23517
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 23804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 30719
telemt_me_reconnect_success_total 19685
telemt_me_reader_eof_total 20686
telemt_me_idle_close_by_peer_total 20686
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 373209
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 920015
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3493
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2277
telemt_desync_frames_bucket_total{bucket="1_2"} 978
telemt_desync_frames_bucket_total{bucket="3_10"} 1170
telemt_desync_frames_bucket_total{bucket="gt_10"} 1345
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 20251
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19641
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 919888
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 11389006912 (10.61 GB)
telemt_user_octets_to_client{user="hello"} 308284491328 (287.11 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 113
```