# Server Metrics 2026-03-14 12:33:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 196471.7 (54h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5705003
telemt_connections_bad_total 62964
telemt_handshake_timeouts_total 125818
telemt_upstream_connect_attempt_total 41258
telemt_upstream_connect_success_total 40995
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 41258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 7852
telemt_me_reconnect_attempts_total 46431
telemt_me_reconnect_success_total 28870
telemt_me_reader_eof_total 31089
telemt_me_idle_close_by_peer_total 31088
telemt_me_route_drop_no_conn_total 2162284
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5231472
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20196
telemt_desync_full_logged_total 5525
telemt_desync_suppressed_total 14671
telemt_desync_frames_bucket_total{bucket="1_2"} 4873
telemt_desync_frames_bucket_total{bucket="3_10"} 7682
telemt_desync_frames_bucket_total{bucket="gt_10"} 7641
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29839
telemt_me_refill_failed_total 543
telemt_me_writer_restored_same_endpoint_total 28857
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 969
telemt_user_connections_total{user="hello"} 5233051
telemt_user_connections_current{user="hello"} 1703
telemt_user_octets_from_client{user="hello"} 81209328488 (75.63 GB)
telemt_user_octets_to_client{user="hello"} 1665549440485 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96135.6 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1107168
telemt_connections_bad_total 58960
telemt_handshake_timeouts_total 25869
telemt_upstream_connect_attempt_total 24624
telemt_upstream_connect_success_total 24317
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 24624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 2408
telemt_me_reconnect_attempts_total 36605
telemt_me_reconnect_success_total 17507
telemt_me_reader_eof_total 18994
telemt_me_idle_close_by_peer_total 18993
telemt_me_route_drop_no_conn_total 375372
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 913836
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2532
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 1732
telemt_desync_frames_bucket_total{bucket="1_2"} 658
telemt_desync_frames_bucket_total{bucket="3_10"} 1052
telemt_desync_frames_bucket_total{bucket="gt_10"} 822
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18350
telemt_me_refill_failed_total 590
telemt_me_writer_restored_same_endpoint_total 17499
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 915747
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 10060314445 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 323935948168 (301.69 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 226092.3 (62h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4045772
telemt_connections_bad_total 46568
telemt_handshake_timeouts_total 278992
telemt_upstream_connect_attempt_total 50875
telemt_upstream_connect_success_total 50854
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11280
telemt_me_reconnect_attempts_total 45259
telemt_me_reconnect_success_total 39255
telemt_me_reader_eof_total 41695
telemt_me_idle_close_by_peer_total 41693
telemt_me_route_drop_no_conn_total 1390532
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3383898
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10834
telemt_desync_full_logged_total 3658
telemt_desync_suppressed_total 7176
telemt_desync_frames_bucket_total{bucket="1_2"} 1982
telemt_desync_frames_bucket_total{bucket="3_10"} 3906
telemt_desync_frames_bucket_total{bucket="gt_10"} 4946
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39836
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39214
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 3383035
telemt_user_connections_current{user="hello"} 973
telemt_user_octets_from_client{user="hello"} 57806721000 (53.84 GB)
telemt_user_octets_to_client{user="hello"} 1206426003417 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 226094.8 (62h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2640079
telemt_connections_bad_total 23515
telemt_handshake_timeouts_total 341782
telemt_upstream_connect_attempt_total 69692
telemt_upstream_connect_success_total 67183
telemt_upstream_connect_fail_total 2372
telemt_upstream_connect_attempts_per_request{bucket="1"} 69418
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2371
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20966
telemt_me_reconnect_attempts_total 61666
telemt_me_reconnect_success_total 48883
telemt_me_reader_eof_total 52372
telemt_me_idle_close_by_peer_total 52364
telemt_me_route_drop_no_conn_total 876477
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2062967
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 194
telemt_me_writer_removed_unexpected_total 49708
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48858
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 825
telemt_user_connections_total{user="hello"} 2069445
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 30613311723 (28.51 GB)
telemt_user_octets_to_client{user="hello"} 735793116174 (685.26 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 95528.7 (26h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1095881
telemt_connections_bad_total 18126
telemt_handshake_timeouts_total 14127
telemt_upstream_connect_attempt_total 23008
telemt_upstream_connect_success_total 22357
telemt_upstream_connect_fail_total 650
telemt_upstream_connect_attempts_per_request{bucket="1"} 23007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 650
telemt_me_keepalive_timeout_total 1796
telemt_me_reconnect_attempts_total 85397
telemt_me_reconnect_success_total 17575
telemt_me_reader_eof_total 20102
telemt_me_idle_close_by_peer_total 20101
telemt_me_route_drop_no_conn_total 442539
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015304
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2719
telemt_desync_full_logged_total 853
telemt_desync_suppressed_total 1866
telemt_desync_frames_bucket_total{bucket="1_2"} 985
telemt_desync_frames_bucket_total{bucket="3_10"} 951
telemt_desync_frames_bucket_total{bucket="gt_10"} 783
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19853
telemt_me_refill_failed_total 2114
telemt_me_writer_restored_same_endpoint_total 17570
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2278
telemt_user_connections_total{user="hello"} 1014502
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 17505410360 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 341697238856 (318.23 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 97
```