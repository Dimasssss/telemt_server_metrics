# Server Metrics 2026-03-11 12:28:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 79285.3 (22h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1829030
telemt_connections_bad_total 27358
telemt_handshake_timeouts_total 47104
telemt_upstream_connect_attempt_total 16442
telemt_upstream_connect_success_total 16433
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 848
telemt_me_reconnect_attempts_total 25249
telemt_me_reconnect_success_total 12423
telemt_me_reader_eof_total 13439
telemt_me_idle_close_by_peer_total 13439
telemt_me_route_drop_no_conn_total 671478
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1667090
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8730
telemt_desync_full_logged_total 2356
telemt_desync_suppressed_total 6374
telemt_desync_frames_bucket_total{bucket="1_2"} 2167
telemt_desync_frames_bucket_total{bucket="3_10"} 3354
telemt_desync_frames_bucket_total{bucket="gt_10"} 3209
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 12957
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12417
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 1665632
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 21945307332 (20.44 GB)
telemt_user_octets_to_client{user="hello"} 472283172820 (439.85 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79342.1 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696438
telemt_connections_bad_total 12930
telemt_handshake_timeouts_total 49409
telemt_upstream_connect_attempt_total 25876
telemt_upstream_connect_success_total 22935
telemt_upstream_connect_fail_total 2941
telemt_upstream_connect_attempts_per_request{bucket="1"} 25876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2941
telemt_me_keepalive_timeout_total 2428
telemt_me_reconnect_attempts_total 16849
telemt_me_reconnect_success_total 15990
telemt_me_reader_eof_total 16919
telemt_me_idle_close_by_peer_total 16916
telemt_me_route_drop_no_conn_total 274908
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584848
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2633
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1802
telemt_desync_frames_bucket_total{bucket="1_2"} 834
telemt_desync_frames_bucket_total{bucket="3_10"} 961
telemt_desync_frames_bucket_total{bucket="gt_10"} 838
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16195
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15967
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 587061
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 6315294462 (5.88 GB)
telemt_user_octets_to_client{user="hello"} 168337438592 (156.78 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 79341.9 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201409
telemt_connections_bad_total 7999
telemt_handshake_timeouts_total 112742
telemt_upstream_connect_attempt_total 21245
telemt_upstream_connect_success_total 20986
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 21245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 858
telemt_me_reconnect_attempts_total 29536
telemt_me_reconnect_success_total 15902
telemt_me_reader_eof_total 17066
telemt_me_idle_close_by_peer_total 17066
telemt_me_route_drop_no_conn_total 404983
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1034431
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2811
telemt_desync_full_logged_total 834
telemt_desync_suppressed_total 1977
telemt_desync_frames_bucket_total{bucket="1_2"} 676
telemt_desync_frames_bucket_total{bucket="3_10"} 1063
telemt_desync_frames_bucket_total{bucket="gt_10"} 1072
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16540
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15891
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 1035172
telemt_user_connections_current{user="hello"} 701
telemt_user_octets_from_client{user="hello"} 12055551417 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 311365301517 (289.98 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 79342.4 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865444
telemt_connections_bad_total 74437
telemt_handshake_timeouts_total 78940
telemt_upstream_connect_attempt_total 21634
telemt_upstream_connect_success_total 21634
telemt_upstream_connect_attempts_per_request{bucket="1"} 21634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 866
telemt_me_reconnect_attempts_total 18717
telemt_me_reconnect_success_total 17652
telemt_me_reader_eof_total 18720
telemt_me_idle_close_by_peer_total 18719
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 277304
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687821
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1460
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 893
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 526
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17865
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17625
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 687180
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 7781816548 (7.25 GB)
telemt_user_octets_to_client{user="hello"} 196748040772 (183.24 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79342.0 (22h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 936124
telemt_connections_bad_total 6256
telemt_handshake_timeouts_total 8833
telemt_upstream_connect_attempt_total 21715
telemt_upstream_connect_success_total 21620
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 21715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 928
telemt_me_reconnect_attempts_total 21579
telemt_me_reconnect_success_total 17516
telemt_me_reader_eof_total 18485
telemt_me_idle_close_by_peer_total 18485
telemt_me_route_drop_no_conn_total 328590
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 849739
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3478
telemt_desync_full_logged_total 1284
telemt_desync_suppressed_total 2194
telemt_desync_frames_bucket_total{bucket="1_2"} 1182
telemt_desync_frames_bucket_total{bucket="3_10"} 1352
telemt_desync_frames_bucket_total{bucket="gt_10"} 944
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17867
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17516
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 849498
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 12562432687 (11.70 GB)
telemt_user_octets_to_client{user="hello"} 306907000026 (285.83 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 89
```