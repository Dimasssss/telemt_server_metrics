# Server Metrics 2026-03-11 11:27:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 75609.8 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1699358
telemt_connections_bad_total 25368
telemt_handshake_timeouts_total 44267
telemt_upstream_connect_attempt_total 15795
telemt_upstream_connect_success_total 15786
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 810
telemt_me_reconnect_attempts_total 24802
telemt_me_reconnect_success_total 11983
telemt_me_reader_eof_total 12958
telemt_me_idle_close_by_peer_total 12958
telemt_me_route_drop_no_conn_total 625609
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1545349
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8160
telemt_desync_full_logged_total 2199
telemt_desync_suppressed_total 5961
telemt_desync_frames_bucket_total{bucket="1_2"} 2065
telemt_desync_frames_bucket_total{bucket="3_10"} 3111
telemt_desync_frames_bucket_total{bucket="gt_10"} 2984
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12504
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 11977
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 1543917
telemt_user_connections_current{user="hello"} 1567
telemt_user_octets_from_client{user="hello"} 20037286084 (18.66 GB)
telemt_user_octets_to_client{user="hello"} 439137510120 (408.98 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75666.4 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 644960
telemt_connections_bad_total 11144
telemt_handshake_timeouts_total 40092
telemt_upstream_connect_attempt_total 24754
telemt_upstream_connect_success_total 21816
telemt_upstream_connect_fail_total 2938
telemt_upstream_connect_attempts_per_request{bucket="1"} 24754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2938
telemt_me_keepalive_timeout_total 2185
telemt_me_reconnect_attempts_total 15934
telemt_me_reconnect_success_total 15086
telemt_me_reader_eof_total 15977
telemt_me_idle_close_by_peer_total 15975
telemt_me_route_drop_no_conn_total 261735
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546798
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2500
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1713
telemt_desync_frames_bucket_total{bucket="1_2"} 811
telemt_desync_frames_bucket_total{bucket="3_10"} 907
telemt_desync_frames_bucket_total{bucket="gt_10"} 782
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15273
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15064
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 549018
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 5648528886 (5.26 GB)
telemt_user_octets_to_client{user="hello"} 154460597908 (143.85 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 75666.3 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1121304
telemt_connections_bad_total 7838
telemt_handshake_timeouts_total 106945
telemt_upstream_connect_attempt_total 20492
telemt_upstream_connect_success_total 20242
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 20492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 825
telemt_me_reconnect_attempts_total 28990
telemt_me_reconnect_success_total 15364
telemt_me_reader_eof_total 16483
telemt_me_idle_close_by_peer_total 16483
telemt_me_route_drop_no_conn_total 376225
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 965354
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2646
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1859
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 993
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15991
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15353
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 966100
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 11244327257 (10.47 GB)
telemt_user_octets_to_client{user="hello"} 293410623697 (273.26 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 75666.6 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812643
telemt_connections_bad_total 71084
telemt_handshake_timeouts_total 75671
telemt_upstream_connect_attempt_total 20501
telemt_upstream_connect_success_total 20501
telemt_upstream_connect_attempts_per_request{bucket="1"} 20501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 814
telemt_me_reconnect_attempts_total 17776
telemt_me_reconnect_success_total 16715
telemt_me_reader_eof_total 17748
telemt_me_idle_close_by_peer_total 17747
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 257905
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642629
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1408
telemt_desync_full_logged_total 540
telemt_desync_suppressed_total 868
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 395
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 16918
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16689
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 641996
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 7400052208 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 182893582268 (170.33 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75666.4 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 874130
telemt_connections_bad_total 6222
telemt_handshake_timeouts_total 8422
telemt_upstream_connect_attempt_total 20620
telemt_upstream_connect_success_total 20528
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 20620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 883
telemt_me_reconnect_attempts_total 20432
telemt_me_reconnect_success_total 16630
telemt_me_reader_eof_total 17539
telemt_me_idle_close_by_peer_total 17539
telemt_me_route_drop_no_conn_total 306172
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 792982
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3281
telemt_desync_full_logged_total 1212
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 1119
telemt_desync_frames_bucket_total{bucket="3_10"} 1296
telemt_desync_frames_bucket_total{bucket="gt_10"} 866
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16962
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 16630
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 792746
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 11886615947 (11.07 GB)
telemt_user_octets_to_client{user="hello"} 287815096110 (268.05 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 100
```