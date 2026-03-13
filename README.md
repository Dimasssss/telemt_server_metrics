# Server Metrics 2026-03-13 19:05:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 133593.8 (37h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4270941
telemt_connections_bad_total 37749
telemt_handshake_timeouts_total 103939
telemt_upstream_connect_attempt_total 28096
telemt_upstream_connect_success_total 27906
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 28096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 6513
telemt_me_reconnect_attempts_total 29009
telemt_me_reconnect_success_total 18894
telemt_me_reader_eof_total 20282
telemt_me_idle_close_by_peer_total 20281
telemt_me_route_drop_no_conn_total 1601732
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3904552
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15375
telemt_desync_full_logged_total 4096
telemt_desync_suppressed_total 11279
telemt_desync_frames_bucket_total{bucket="1_2"} 3825
telemt_desync_frames_bucket_total{bucket="3_10"} 5854
telemt_desync_frames_bucket_total{bucket="gt_10"} 5696
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 19479
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18881
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 3906721
telemt_user_connections_current{user="hello"} 1640
telemt_user_octets_from_client{user="hello"} 55172598524 (51.38 GB)
telemt_user_octets_to_client{user="hello"} 1225283861821 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33257.6 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487109
telemt_connections_bad_total 38065
telemt_handshake_timeouts_total 10942
telemt_upstream_connect_attempt_total 9866
telemt_upstream_connect_success_total 9655
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 9866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3743
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 1863
telemt_me_reconnect_attempts_total 9374
telemt_me_reconnect_success_total 5963
telemt_me_reader_eof_total 6302
telemt_me_idle_close_by_peer_total 6301
telemt_me_route_drop_no_conn_total 183136
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423547
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1491
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 1092
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 516
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6152
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5955
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 425476
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 4511395997 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 134121732512 (124.91 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 163214.3 (45h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3121417
telemt_connections_bad_total 29160
telemt_handshake_timeouts_total 209077
telemt_upstream_connect_attempt_total 36292
telemt_upstream_connect_success_total 36277
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10161
telemt_me_reconnect_attempts_total 30380
telemt_me_reconnect_success_total 27817
telemt_me_reader_eof_total 29485
telemt_me_idle_close_by_peer_total 29484
telemt_me_route_drop_no_conn_total 1066889
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2580119
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8674
telemt_desync_full_logged_total 2869
telemt_desync_suppressed_total 5805
telemt_desync_frames_bucket_total{bucket="1_2"} 1417
telemt_desync_frames_bucket_total{bucket="3_10"} 3177
telemt_desync_frames_bucket_total{bucket="gt_10"} 4080
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 28146
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27776
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 2579412
telemt_user_connections_current{user="hello"} 876
telemt_user_octets_from_client{user="hello"} 42393164572 (39.48 GB)
telemt_user_octets_to_client{user="hello"} 905777811709 (843.57 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 163214.9 (45h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2008958
telemt_connections_bad_total 21514
telemt_handshake_timeouts_total 183593
telemt_upstream_connect_attempt_total 51474
telemt_upstream_connect_success_total 49040
telemt_upstream_connect_fail_total 2297
telemt_upstream_connect_attempts_per_request{bucket="1"} 51200
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2296
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20171
telemt_me_reconnect_attempts_total 42879
telemt_me_reconnect_success_total 33873
telemt_me_reader_eof_total 36371
telemt_me_idle_close_by_peer_total 36364
telemt_me_route_drop_no_conn_total 715158
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1658647
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3460
telemt_desync_full_logged_total 1112
telemt_desync_suppressed_total 2348
telemt_desync_frames_bucket_total{bucket="1_2"} 928
telemt_desync_frames_bucket_total{bucket="3_10"} 1421
telemt_desync_frames_bucket_total{bucket="gt_10"} 1111
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 34434
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33849
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 1664519
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 25516783559 (23.76 GB)
telemt_user_octets_to_client{user="hello"} 630379447022 (587.09 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32650.5 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528074
telemt_connections_bad_total 5564
telemt_handshake_timeouts_total 5263
telemt_upstream_connect_attempt_total 7093
telemt_upstream_connect_success_total 6855
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 7093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 954
telemt_me_reconnect_attempts_total 26122
telemt_me_reconnect_success_total 5188
telemt_me_reader_eof_total 5932
telemt_me_idle_close_by_peer_total 5931
telemt_me_route_drop_no_conn_total 200279
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494264
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1439
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 989
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 430
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5884
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5184
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 696
telemt_user_connections_total{user="hello"} 494238
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 5744220880 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 158365292340 (147.49 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 98
```