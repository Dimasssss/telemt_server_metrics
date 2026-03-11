# Server Metrics 2026-03-11 00:51:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 37457.3 (10h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 795756
telemt_connections_bad_total 9523
telemt_handshake_timeouts_total 9058
telemt_upstream_connect_attempt_total 8160
telemt_upstream_connect_success_total 8151
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 8160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 477
telemt_me_reconnect_attempts_total 17878
telemt_me_reconnect_success_total 6213
telemt_me_reader_eof_total 6809
telemt_me_idle_close_by_peer_total 6809
telemt_me_route_drop_no_conn_total 327404
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753423
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3557
telemt_desync_full_logged_total 995
telemt_desync_suppressed_total 2562
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6628
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 6207
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 753199
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 10485762912 (9.77 GB)
telemt_user_octets_to_client{user="hello"} 226299530832 (210.76 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 37514.0 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343392
telemt_connections_bad_total 2391
telemt_handshake_timeouts_total 17663
telemt_upstream_connect_attempt_total 15244
telemt_upstream_connect_success_total 12364
telemt_upstream_connect_fail_total 2880
telemt_upstream_connect_attempts_per_request{bucket="1"} 15244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2880
telemt_me_keepalive_timeout_total 1707
telemt_me_reconnect_attempts_total 8325
telemt_me_reconnect_success_total 7511
telemt_me_reader_eof_total 7925
telemt_me_idle_close_by_peer_total 7923
telemt_me_route_drop_no_conn_total 172933
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292755
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1768
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 1266
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 626
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7614
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7490
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 295024
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 2842218746 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 70387393872 (65.55 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 37513.9 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 570824
telemt_connections_bad_total 4053
telemt_handshake_timeouts_total 34139
telemt_upstream_connect_attempt_total 10289
telemt_upstream_connect_success_total 10146
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 10289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 510
telemt_me_reconnect_attempts_total 18227
telemt_me_reconnect_success_total 7166
telemt_me_reader_eof_total 7816
telemt_me_idle_close_by_peer_total 7816
telemt_me_route_drop_no_conn_total 195732
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504077
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1522
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 7609
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 7155
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 504998
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 6835167089 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 155090418093 (144.44 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 37514.2 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418160
telemt_connections_bad_total 35687
telemt_handshake_timeouts_total 39327
telemt_upstream_connect_attempt_total 10714
telemt_upstream_connect_success_total 10714
telemt_upstream_connect_attempts_per_request{bucket="1"} 10714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 407
telemt_me_reconnect_attempts_total 9840
telemt_me_reconnect_success_total 8808
telemt_me_reader_eof_total 9311
telemt_me_idle_close_by_peer_total 9311
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 128774
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330100
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 720
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 431
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 250
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 8925
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8792
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 329776
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 4206842640 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 91042192044 (84.79 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 37514.0 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442310
telemt_connections_bad_total 4404
telemt_handshake_timeouts_total 2771
telemt_upstream_connect_attempt_total 11310
telemt_upstream_connect_success_total 11263
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 11310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5291
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 504
telemt_me_reconnect_attempts_total 13089
telemt_me_reconnect_success_total 9322
telemt_me_reader_eof_total 9806
telemt_me_idle_close_by_peer_total 9806
telemt_me_route_drop_no_conn_total 147544
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407254
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2274
telemt_desync_full_logged_total 879
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 838
telemt_desync_frames_bucket_total{bucket="3_10"} 971
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 9561
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 9322
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 406981
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 8360748336 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 146759527824 (136.68 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 31
```