# Server Metrics 2026-03-13 05:17:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 83943.1 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2260659
telemt_connections_bad_total 32978
telemt_handshake_timeouts_total 23737
telemt_upstream_connect_attempt_total 16546
telemt_upstream_connect_success_total 16454
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1309
telemt_me_reconnect_attempts_total 21129
telemt_me_reconnect_success_total 12262
telemt_me_reader_eof_total 13233
telemt_me_idle_close_by_peer_total 13232
telemt_me_route_drop_no_conn_total 861239
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2078942
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9197
telemt_desync_full_logged_total 2371
telemt_desync_suppressed_total 6826
telemt_desync_frames_bucket_total{bucket="1_2"} 2405
telemt_desync_frames_bucket_total{bucket="3_10"} 3343
telemt_desync_frames_bucket_total{bucket="gt_10"} 3449
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 12709
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12249
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 2078334
telemt_user_connections_current{user="hello"} 1264
telemt_user_octets_from_client{user="hello"} 30142145584 (28.07 GB)
telemt_user_octets_to_client{user="hello"} 715966892976 (666.80 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 113563.6 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 917480
telemt_connections_bad_total 12375
telemt_handshake_timeouts_total 40105
telemt_upstream_connect_attempt_total 28769
telemt_upstream_connect_success_total 28738
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 28769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3538
telemt_me_reconnect_attempts_total 21546
telemt_me_reconnect_success_total 21429
telemt_me_reader_eof_total 22844
telemt_me_idle_close_by_peer_total 22844
telemt_me_route_drop_no_conn_total 292187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 826960
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3262
telemt_desync_full_logged_total 1030
telemt_desync_suppressed_total 2232
telemt_desync_frames_bucket_total{bucket="1_2"} 1300
telemt_desync_frames_bucket_total{bucket="3_10"} 1069
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 21640
telemt_me_writer_restored_same_endpoint_total 21420
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 828854
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 13268553464 (12.36 GB)
telemt_user_octets_to_client{user="hello"} 317271803511 (295.48 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 113563.5 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1895907
telemt_connections_bad_total 19339
telemt_handshake_timeouts_total 124544
telemt_upstream_connect_attempt_total 26438
telemt_upstream_connect_success_total 26428
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1644
telemt_me_reconnect_attempts_total 21680
telemt_me_reconnect_success_total 20410
telemt_me_reader_eof_total 21621
telemt_me_idle_close_by_peer_total 21620
telemt_me_route_drop_no_conn_total 609507
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1493887
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5171
telemt_desync_full_logged_total 1584
telemt_desync_suppressed_total 3587
telemt_desync_frames_bucket_total{bucket="1_2"} 838
telemt_desync_frames_bucket_total{bucket="3_10"} 1865
telemt_desync_frames_bucket_total{bucket="gt_10"} 2468
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 20607
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20369
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 1493385
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 25666848888 (23.90 GB)
telemt_user_octets_to_client{user="hello"} 531594211601 (495.09 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 113563.8 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1165026
telemt_connections_bad_total 13839
telemt_handshake_timeouts_total 75557
telemt_upstream_connect_attempt_total 38870
telemt_upstream_connect_success_total 36585
telemt_upstream_connect_fail_total 2148
telemt_upstream_connect_attempts_per_request{bucket="1"} 38596
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2147
telemt_me_keepalive_timeout_total 11397
telemt_me_reconnect_attempts_total 33986
telemt_me_reconnect_success_total 25052
telemt_me_reader_eof_total 27038
telemt_me_idle_close_by_peer_total 27031
telemt_me_route_drop_no_conn_total 414715
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1002931
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1975
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1325
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 768
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 25502
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25028
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 1008113
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 15367895069 (14.31 GB)
telemt_user_octets_to_client{user="hello"} 398105885690 (370.76 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 113563.8 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1301538
telemt_connections_bad_total 12925
telemt_handshake_timeouts_total 10396
telemt_upstream_connect_attempt_total 35941
telemt_upstream_connect_success_total 35507
telemt_upstream_connect_fail_total 434
telemt_upstream_connect_attempts_per_request{bucket="1"} 35941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 434
telemt_me_keepalive_timeout_total 1958
telemt_me_reconnect_attempts_total 43574
telemt_me_reconnect_success_total 29841
telemt_me_reader_eof_total 31361
telemt_me_idle_close_by_peer_total 31361
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 481654
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1205112
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4367
telemt_desync_full_logged_total 1571
telemt_desync_suppressed_total 2796
telemt_desync_frames_bucket_total{bucket="1_2"} 1320
telemt_desync_frames_bucket_total{bucket="3_10"} 1420
telemt_desync_frames_bucket_total{bucket="gt_10"} 1627
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 30604
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 29790
telemt_me_writer_restored_fallback_total 51
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1204969
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 14626916828 (13.62 GB)
telemt_user_octets_to_client{user="hello"} 408934359916 (380.85 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 76
```