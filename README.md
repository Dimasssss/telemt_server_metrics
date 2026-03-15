# Server Metrics 2026-03-15 18:35:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 73271.8 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2635393
telemt_connections_bad_total 152053
telemt_handshake_timeouts_total 35555
telemt_upstream_connect_attempt_total 14119
telemt_upstream_connect_success_total 14058
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 14119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15286
telemt_me_reconnect_success_total 10387
telemt_me_reader_eof_total 11105
telemt_me_idle_close_by_peer_total 11105
telemt_me_route_drop_no_conn_total 914410
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2202240
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8521
telemt_desync_full_logged_total 2335
telemt_desync_suppressed_total 6186
telemt_desync_frames_bucket_total{bucket="1_2"} 2102
telemt_desync_frames_bucket_total{bucket="3_10"} 3258
telemt_desync_frames_bucket_total{bucket="gt_10"} 3161
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10716
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10376
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 2201706
telemt_user_connections_current{user="hello"} 2310
telemt_user_octets_from_client{user="hello"} 33360881916 (31.07 GB)
telemt_user_octets_to_client{user="hello"} 839425100480 (781.78 GB)
telemt_user_unique_ips_current{user="hello"} 666
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 73272.2 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020997
telemt_connections_bad_total 59101
telemt_handshake_timeouts_total 64604
telemt_upstream_connect_attempt_total 18099
telemt_upstream_connect_success_total 18001
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 18099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 15183
telemt_me_reconnect_success_total 13970
telemt_me_reader_eof_total 14787
telemt_me_idle_close_by_peer_total 14787
telemt_me_route_drop_no_conn_total 265106
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 789936
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2257
telemt_desync_full_logged_total 774
telemt_desync_suppressed_total 1483
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 856
telemt_desync_frames_bucket_total{bucket="gt_10"} 619
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14192
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13958
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 790165
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 11405912807 (10.62 GB)
telemt_user_octets_to_client{user="hello"} 297000390504 (276.60 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 73272.4 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2222460
telemt_connections_bad_total 51242
telemt_handshake_timeouts_total 216014
telemt_upstream_connect_attempt_total 15709
telemt_upstream_connect_success_total 15629
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 15709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 13198
telemt_me_reconnect_success_total 11928
telemt_me_reader_eof_total 12641
telemt_me_idle_close_by_peer_total 12641
telemt_me_route_drop_no_conn_total 580647
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1401752
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3695
telemt_desync_full_logged_total 1330
telemt_desync_suppressed_total 2365
telemt_desync_frames_bucket_total{bucket="1_2"} 844
telemt_desync_frames_bucket_total{bucket="3_10"} 1443
telemt_desync_frames_bucket_total{bucket="gt_10"} 1408
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12138
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11909
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 1397624
telemt_user_connections_current{user="hello"} 1405
telemt_user_octets_from_client{user="hello"} 25894430568 (24.12 GB)
telemt_user_octets_to_client{user="hello"} 528274479572 (491.99 GB)
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 73272.1 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1084515
telemt_connections_bad_total 82095
telemt_handshake_timeouts_total 53129
telemt_upstream_connect_attempt_total 171145
telemt_upstream_connect_success_total 170535
telemt_upstream_connect_fail_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 171145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 610
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61960
telemt_me_reconnect_success_total 13894
telemt_me_reader_eof_total 15778
telemt_me_idle_close_by_peer_total 15778
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 259150
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693880
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1933
telemt_desync_full_logged_total 539
telemt_desync_suppressed_total 1394
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 745
telemt_desync_frames_bucket_total{bucket="gt_10"} 698
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 15540
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13858
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 846391
telemt_user_connections_current{user="hello"} 900
telemt_user_octets_from_client{user="hello"} 15520066045 (14.45 GB)
telemt_user_octets_to_client{user="hello"} 301995566428 (281.26 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 73272.9 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1101264
telemt_connections_bad_total 12685
telemt_handshake_timeouts_total 23633
telemt_upstream_connect_attempt_total 16029
telemt_upstream_connect_success_total 15943
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 16029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15959
telemt_me_reconnect_success_total 12264
telemt_me_reader_eof_total 13083
telemt_me_idle_close_by_peer_total 13083
telemt_me_route_drop_no_conn_total 278584
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 914409
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3213
telemt_desync_full_logged_total 1057
telemt_desync_suppressed_total 2156
telemt_desync_frames_bucket_total{bucket="1_2"} 972
telemt_desync_frames_bucket_total{bucket="3_10"} 1179
telemt_desync_frames_bucket_total{bucket="gt_10"} 1062
telemt_pool_swap_total 62
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12527
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 12256
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 914430
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 11300546144 (10.52 GB)
telemt_user_octets_to_client{user="hello"} 319837063664 (297.87 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 118
```